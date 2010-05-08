These templates reduce the amount of keystrokes required to write NUnit tests. The tdd-livetemplates.xml file is in a format that can be imported into Jetbrains Resharper. The live templates introduce the following templates:

`test`
    [Test]
    public void TESTNAME()
    {

    }

`tf`
    using NUnit.Framework;

    namespace NAMESPACE
    {
        [TestFixture]
        public class CLASSNAMEFixture
        {
            [Test]
            public void TESTNAME()
            {
        
            }
        }
    }

`te`
    [Test]
    [ExpectedException(typeof(EXCEPTIONTYPE))]
    public void TESTNAME()
    {

    }

`ti`
    [SetUp]
    public void TestInitialize()
    {

    }

`td`
    [TearDown]
    public void TestCleanup()
    {

    }