# junit_learn

2.@Test：标记为测试方法。
注解成员有：（1）timeout=100ms,超时验证
 （2）expected=异常class，抛出异常验证
3.@Ignore：忽略此测试方法。
4.@BeforeClass，在开始执行整个类的测试方法前，先执行一次该方法。申请资源等。
@AfterClass，在执行完整个类的测试方法后，执行一次该方法。释放资源等。
@Before，在执行整个类的每个测试方法前，执行一次该方法。
@After，在执行完整个类的每个测试方法后，执行一次该方法。
5.@FixMethodOrder，指定测试方法的顺序，
