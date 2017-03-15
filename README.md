# Advance Topic in Android
Here you will get all the advance concept in android like Memory management, Bitmap Memory management, Database with thread safe etc

1. Bitmap Memory Management
2. MVP : Model View Presenter Architecture
3. MVVM : Model View ViewModel Design Pattern
4. DataBinding and 2 way data Binding 
5. 



#Dagger 2
#1. Main Components of Dagger 2

1. @Module : Classes annotated with @Module are responsible for providing objects which can be injected. Such classes define methods annotated with @Provides. The returned objects from these methods are available for dependency injection.
2. @Inject : Known as Dependency consumer, The @Inject annotation is used to define a dependency.
3. @Component : A @Component annotated interface defines the connection between the provider of objects (modules) and the objects which express a dependency. The class for this connection is generated by the Dagger.

# Limitations Of Dagger 2
    Dagger2 does not inject fields automatically.
    It cannot inject private fields.
    If you want to use field injection you have to define a method in your @Component annotated interface which takes the instance of the class into which you want to inject the member variable.
