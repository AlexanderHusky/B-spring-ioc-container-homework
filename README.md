
954/5000
@Component使用类路径扫描自动检测并配置Bean，而@Bean显式声明单个Bean，而不是让Spring自动执行。
@Component不会将bean的声明与类定义解耦，而@Bean会将bean的声明与类定义解耦。
@Component是类级别的注释，而@Bean是方法级别的注释，该方法的名称用作Bean名称。
@Component不必与@Configuration注释一起使用，因为必须在@Configuration注释的类中使用@Bean注释。
如果类在spring容器之外，则无法使用@Component创建类的bean，而即使类在spring容器之外，也可以使用@Bean创建类的bean。
@Component具有不同的专长，例如@ Controller，@ Repository和@Service，而@Bean没有专长。
