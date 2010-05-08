These templates reduce the amount of keystrokes required to write NUnit tests. The tdd-livetemplates.xml file is in a format that can be imported into Jetbrains Resharper. The live templates introduce the following templates:

    // typing test and hitting TAB invokes this template
    [Test]
    public void TESTNAME()
    {

    }

    // typing tf and hitting TAB invokes this template
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

    // typing te and hitting TAB invokes this template
    [Test]
    [ExpectedException(typeof(EXCEPTIONTYPE))]
    public void TESTNAME()
    {

    }

    // typing ti and hitting TAB invokes this template
    [SetUp]
    public void TestInitialize()
    {

    }

    // typing td and hitting TAB invokes this template    
    [TearDown]
    public void TestCleanup()
    {

    }