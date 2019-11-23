![Background Image](https://github.com/CodemyLive/Kotlin-Syllabus/blob/master/assets/bg_kotlin.jpg)
* **Hazırlayan**      : Gökhan ÖZTÜRK | [GokhanOzturk@AndroidEdu.IO](mailto:GokhanOzturk@AndroidEdu.IO)
* **Katkı Sunanlar**  : ---
* **Kotlin Version**  : v1.3.60

### Yardıma ihtiyacın mı var?

[![Discord](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_discord.png)](https://discord.gg/nDTD4TQ)	

***

* Syllabus'a, derslerden önce, yarım saat ayırıp -bir ön çalışma yapmak için inceleyecek kadar bu işi sevmiyorsanız, güzel bir film açıp izleyin ya da harika bir müzik keşfedin. Zaman hepimiz için değerli, yarın bırakacağınız şeyler için bugün sahip olduğunuz dakikaları öldürmeyin. "Keko'ya anlatır gibi anlat bana! Nasıl aratacağım bunları..", diyorsanız bu da kıyağım olsundu, tıklayın -> [![Örnek Google Sorgusu !](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_search.png)](http://bit.ly/codemy-kotlin-search)
* Bu arada: "Keko gibi bir eğitim olmuş; şunları da ekle, bunlar eksik kalmış... Bu işin, şöyle bir 'trick' noktası var..", dediğiniz bir şeyler varsa bi [Pull Request](https://github.com/CodemyLive/Kotlin-Syllabus/pulls)'inizi alırız :*

***

# Program Açıklaması

Bu program ile IntelliJ IDEA idesi üzerinde, nasıl ninja kod yazılır bunu öğretmeye; beraber öğrenmeye çalışacağız. Java - Kotlin benzerliklerinden ve ayrıştıkları noktalardan tonlarca örnek vereceğiz. Sadece Kotlin Syntax'ıyla yazmayı değil aynı zamanda Fonksiyonel programlama prensipleriyle düşünebilmeyi öğreneceğiz. Günün sonunda Java'nın herkesin aşık olduğu populer sevgili olduğunu, Kotlin'in ise, "o hep beklediğiniz saf aşk" olduğunu iliklerinize kadar hissedeceksiniz. <3

# Ön Şartlar

5 yaşındaki bir çocuğa: "Çay Nasıl Demlenir?"i adım adım anlatabilecek kadar ya da Kinder Süpriz Yumurta'nın içerisindeki talimatları yerine getirerek -parçaları birleştirip bir bütün hale getirecek kadar minnoş bir akla sahipseniz çokça yeterli. Yok analitik düşünceymiş, yok matematikmiş.. Sensin o matematik!

# Programa Genel Bakış

Size saatlerce Kotlin adasının tarihçesini, kahve nasıl yapılırı anlatmayacağız. Ama Kotlin ne zaman başladı, neden Google tarafından "First Class Language" desteği aldı, Oracle Google'ı neden tokatlıyor, bu milyar dolarlık dava da neyin nesi anlatamadan başlayamayız. Bu sebeple Kim 500 bin TL ister yarışmasında çıksa cevaplayabileceğiniz kadar bir genel kültürle başlayıp devamında aşağıdaki konuları farklı zamanlarda gündeme getirerek Kotlin'i "Ninja" seviyesinde uçtan uca anlatacağız; öğrenecğiz. Konu başlıklarını Türkçe yazmayacağım; zira takım arkadaşlarınız bu teknolojilerden bahsederken Türkçe konuşmayacaklar. Hayatın gerçekleri ile fantazi isteklerimiz ne yazık ki birbirini tutmuyor. Ayrıca sabır eşiğiniz yıkılıp da yurtdışında çalışmaya gittiğinizde kimse sizle Türkçe konuşmayacak.

# Önemli Not

      Eğitim içeriğinde bulunan tüm konular anlatılmayacaktır. Üstelik size verdiğim sırayla -art arda da anlatılmayacaktır. Zira ezbere bir eğitim değil; anlayarak, uygulayarak bir şeyler inşaa edebilmenizi sağlamak istiyoruz. Bu sebeple bazı konuların anlatımı daha sonraya kalacakken bazı konular ise: "Tamam.., her şeyi hallettim, başka ne var?", dediğinizde size yol göstermesi için buraya eklenmişlerdir.

***

# Getting Started

### Basic Syntax

* Package definition and imports
* Program entry point
* Functions
* Variables
* Comments
* String templates
* Conditional expressions
* Nullable values and null checks
* Type checks and automatic casts
* for loop
* while loop
* when expression
* Ranges
* Collections
* Creating basic classes and their instances

### Idioms

* Creating DTOs (POJOs/POCOs)
* Default values for function parameters
* Filtering a list
* Checking element presence in a collection
* String Interpolation
* Instance Checks
* Traversing a map/list of pairs
* Using ranges
* Read-only list
* Read-only map
* Accessing a map
* Lazy property
* Extension Functions
* Creating a singleton
* If not null shorthand
* If not null and else shorthand
* Executing a statement if null
* Get first item of a possibly empty collection
* Execute if not null
* Map nullable value if not null
* Return on when statement
* 'try/catch' expression
* 'if' expression
* Builder-style usage of methods that return Unit
* Single-expression functions
* Calling multiple methods on an object instance (with)
* Configuring properties of an object (apply)
* Java 7's try with resources
* Convenient form for a generic function that requires the generic type information
* Consuming a nullable Boolean
* Swapping two variables
* TODO(): Marking code as incomplete

### Coding Conventions

* Applying the style guide
* Directory structure
* Source file names
* Source file organization
* Class layout
* Interface implementation layout
* Overload layout
* Naming rules
* Function names
* Property names
* Choosing good names
* Formatting
* Horizontal whitespace
* Colon
* Class header formatting
* Modifiers
* Annotation formatting
* File annotations
* Function formatting
* Expression body formatting
* Property formatting
* Formatting control flow statements
* Method call formatting
* Chained call wrapping
* Lambda formatting
* Documentation comments
* Avoiding redundant constructs
* Unit
* Semicolons
* String templates
* Idiomatic use of language features
* Immutability
* Default parameter values
* Type aliases
* Lambda parameters
* Returns in a lambda
* Named arguments
* Using conditional statements
* if versus when
* Using nullable Boolean values in conditions
* Using loops
* Loops on ranges
* Using strings
* Functions vs Properties
* Using extension functions
* Using infix functions
* Factory functions
* Platform types
* Using scope functions apply/with/run/also/let
* Coding conventions for libraries

***

# Basics

### Basic Types

* Numbers
* Literal constants
* Underscores in numeric literals (since 1.1)
* Representation
* Explicit conversions
* Operations
* Floating point numbers comparison
* Characters
* Booleans
* Arrays
* Primitive type arrays
* Unsigned integers
* Specialized classes
* Literals
* Experimental status of unsigned integers
* Strings
* String literals
* String templates

### Packages and Imports

* Packages
* Default Imports
* Imports
* Visibility of Top-level Declarations

### Control Flow

* If Expression
* When Expression
* For Loops
* While Loops
* Break and continue in loops

### Returns and Jumps

* Break and Continue Labels
* Return at Labels

***

# Classes & Objects

### Classes and Inheritance

* Classes
* Constructors
* Secondary constructors
* Creating instances of classes
* Class members
* Inheritance
* Overriding methods
* Overriding properties
* Derived class initialization order
* Calling the superclass implementation
* Overriding rules
* Abstract classes
* Companion objects

### Properties and Fields

* Declaring Properties
* Getters and Setters
* Backing Fields
* Backing Properties
* Compile-Time Constants
* Late-Initialized Properties and Variables
* Checking whether a lateinit var is initialized (since 1.2)
* Overriding Properties
* Delegated Properties

### Interfaces

* Interfaces
* Implementing Interfaces
* Properties in Interfaces
* Interfaces Inheritance
* Resolving overriding conflicts

### Visibility Modifiers

* Visibility Modifiers
* Packages
* Classes and Interfaces
* Constructors
* Local declarations
* Modules

### Extensions

* Extensions
* Extension functions
* Extensions are resolved statically
* Nullable receiver
* Extension properties
* Companion object extensions
* Scope of extensions
* Declaring extensions as members
* Note on visibility

### Data Classes

* Data Classes
* Properties Declared in the Class Body
* Copying
* Data Classes and Destructuring Declarations
* Standard Data Classes

### Sealed Classes

* Sealed Classes

### Generics

* Generics
* Variance
* Declaration-site variance
* Use-site variance: Type projections
* Star-projections
* Generic functions
* Generic constraints
* Upper bounds
* Type erasure

### Nested Classes

* Nested and Inner Classes
* Inner classes
* Anonymous inner classes

### Enum Classes

* Enum Classes
* Initialization
* Anonymous Classes
* Implementing Interfaces in Enum Classes
* Working with Enum Constants

### Objects

* Object Expressions and Declarations
* Object expressions
* Object declarations
* Companion Objects
* Semantic difference between object expressions and declarations

### Type Aliases

* Type aliases

### Inline Classes

* Inline classes
* Members
* Inheritance
* Representation
* Mangling
* Inline classes vs type aliases
* Experimental status of inline classes
* Enabling inline classes in Gradle
* Enabling inline classes in Maven

### Delegation

* Property Delegation
* Implementation by Delegation
* Overriding a member of an interface implemented by delegation

### Delegated Properties

* Delegated Properties
* Standard Delegates
* Lazy
* Observable
* Storing Properties in a Map
* Local Delegated Properties (since 1.1)
* Property Delegate Requirements
* Translation Rules
* Providing a delegate (since 1.1)

***

# Functions & Lambdas

### Functions

* Function declarations
* Function usage
* Parameters
* Default arguments
* Named arguments
* Unit-returning functions
* Single-expression functions
* Explicit return types
* Variable number of arguments (Varargs)
* Infix notation
* Function scope
* Local functions
* Member functions
* Generic functions
* Inline functions
* Extension functions
* Higher-order functions and lambdas
* Tail recursive functions

### Lambdas

* Higher-Order Functions and Lambdas
* Higher-Order Functions
* Function types
* Instantiating a function type
* Invoking a function type instance
* Inline functions
* Lambda Expressions and Anonymous Functions
* Lambda expression syntax
* Passing a lambda to the last parameter
* it: implicit name of a single parameter
* Returning a value from a lambda expression
* Underscore for unused variables (since 1.1)
* Destructuring in lambdas (since 1.1)
* Anonymous functions
* Closures
* Function literals with receiver

### Inline Functions

* Inline Functions
* noinline
* Non-local returns
* Reified type parameters
* Inline properties (since 1.1)
* Restrictions for public API inline functions

***

# Collections

### Collections Overview

* Collection types
* Collection
* List
* Set
* Map

### Constructing Collections

* Constructing from elements
* Empty collections
* Initializer functions for lists
* Concrete type constructors
* Copying
* Invoking functions on other collections

### Iterators

* Iterators
* List iterators
* Mutable iterators

### Ranges and Progressions

* Ranges and Progressions
* Range
* Progression

### Sequences

* Sequences
* Constructing
* From elements
* From Iterable
* From function
* From chunks
* Sequence operations
* Sequence processing example
* Iterable
* Sequence

### Operations Overview

* Collection Operations Overview
* Extension and member functions
* Common operations
* Write operations

### Transformations

* Collection Transformations
* Mapping
* Zipping
* Association
* Flattening
* String representation

### Filtering

* Filtering
* Filtering by predicate
* Partitioning
* Testing predicates

### Plus and Minus Operators

* plus and minus Operators

### Grouping

* Grouping

### Retrieving Collection Parts

* Retrieving Collection Parts
* Slice
* Take and drop
* Chunked
* Windowed

### Retrieving Single Elements

* Retrieving Single Elements
* Retrieving by position
* Retrieving by condition
* Random element
* Checking existence

### Ordering

* Collection Ordering
* Natural order
* Custom orders
* Reverse order
* Random order

### Aggregate Operations

* Collection Aggregate Operations
* Fold and reduce

### Collection Write Operations

* Collection Write Operations
* Adding elements
* Removing elements
* Updating elements

### List Specific Operations

* List Specific Operations
* Retrieving elements by index
* Retrieving list parts
* Finding element positions
* Linear search
* Binary search in sorted lists
* Comparator binary search
* Comparison binary search
* List write operations
* Adding
* Updating
* Removing
* Sorting

### Set Specific Operations

* Set Specific Operations

### Map Specific Operations

* Map Specific Operations
* Retrieving keys and values
* Filtering
* plus and minus operators
* Map write operations
* Adding and updating entries
* Removing entries

***

# Others

### Destructuring Declarations

* Destructuring Declarations
* Example: Returning Two Values from a Function
* Example: Destructuring Declarations and Maps
* Underscore for unused variables (since 1.1)
* Destructuring in Lambdas (since 1.1)

### Type Checks and Casts

* is and !is Operators
* Smart Casts
* "Unsafe" cast operator
* "Safe" (nullable) cast operator
* Type erasure and generic type checks
* Unchecked casts

### This expressions

* This Expression
* Qualified this

### Equality 🌈

* Equality
* Structural equality
* Floating point numbers equality
* Referential equality

### Operator overloading

* Operator overloading
* Unary prefix operators
* Increments and decrements
* Arithmetic operators
* 'In' operator
* Indexed access operator
* Invoke operator
* Augmented assignments
* Equality and inequality operators
* Comparison operators
* Property delegation operators
* Infix calls for named functions

### Null Safety

* Nullable types and Non-Null Types
* Checking for null in conditions
* Safe Calls
* Elvis Operator
* The !! Operator
* Safe Casts
* Collections of Nullable Type

### Exceptions

* Exception Classes
* Try is an expression
* Checked Exceptions
* The Nothing type
* Java Interoperability

### Annotations

* Annotation Declaration
* Usage
* Constructors
* Lambdas
* Annotation Use-site Targets
* Java Annotations
* Arrays as annotation parameters
* Accessing properties of an annotation instance

### Reflection

* Reflection
* Class References
* Bound Class References (since 1.1)
* Callable references
* Function References
* Example: Function Composition
* Property References
* Interoperability With Java Reflection
* Constructor References
* Bound Function and Property References (since 1.1)
* Bound constructor references

### Scope Functions

* Scope Functions
* Distinctions
* Context object: this or it
* this
* it
* Return value
* Context object
* Lambda result
* let
* with
* run
* apply
* also
* Function selection
* takeIf and takeUnless

### Type-Safe Builders

* Type-Safe Builders
* A type-safe builder example
* How it works
* Scope control: DslMarker (since 1.1)
* Full definition of the com.example.html package

### Experimental API Markers

* Experimental API Markers
* Using experimental APIs
* Propagating use
* Non-propagating use
* Module-wide use
* Creating marker annotations
* Marking API elements
* Module-wide markers
* Graduation of experimental API
* Experimental status of experimental API markers

***

# Coroutines

### Basics

* Your first coroutine
* Bridging blocking and non-blocking worlds
* Waiting for a job
* Structured concurrency
* Scope builder
* Extract function refactoring
* Coroutines ARE light-weight
* Global coroutines are like daemon threads

### Cancellation and Timeouts

* Cancelling coroutine execution
* Cancellation is cooperative
* Making computation code cancellable
* Closing resources with finally
* Run non-cancellable block
* Timeout

### Composing Suspending Functions

* Sequential by default
* Concurrent using async
* Lazily started async
* Async-style functions
* Structured concurrency with async

### Coroutine Context and Dispatchers

* Coroutine Context and Dispatchers
* Dispatchers and threads
* Unconfined vs confined dispatcher
* Debugging coroutines and threads
* Jumping between threads
* Job in the context
* Children of a coroutine
* Parental responsibilities
* Naming coroutines for debugging
* Combining context elements
* Coroutine scope
* Thread-local data

### Asynchronous Flow

* Representing multiple values
* Sequences
* Suspending functions
* Flows
* Flows are cold
* Flow cancellation
* Flow builders
* Intermediate flow operators
* Transform operator
* Size-limiting operators
* Terminal flow operators
* Flows are sequential
* Flow context
* Wrong emission withContext
* flowOn operator
* Buffering
* Conflation
* Processing the latest value
* Zip
* Combine
* Flattening flows
* flatMapConcat
* flatMapMerge
* flatMapLatest
* Collector try and catch
* Everything is caught
* Exception transparency
* Transparent catch
* Catching declaratively
* Imperative finally block
* Declarative handling
* Upstream exceptions only
* Imperative versus declarative
* Launching flow
* Flow and Reactive Streams

### Channels

* Channel basics
* Closing and iteration over channels
* Building channel producers
* Pipelines
* Prime numbers with pipeline
* Fan-out
* Fan-in
* Buffered channels
* Channels are fair
* Ticker channels

### Exception Handling and Supervision

* Exception Handling
* Exception propagation
* CoroutineExceptionHandler
* Cancellation and exceptions
* Exceptions aggregation
* Supervision
* Supervision job
* Supervision scope
* Exceptions in supervised coroutines

### Shared Mutable State and Concurrency

* Shared mutable state and concurrency
* Volatiles are of no help
* Thread-safe data structures
* Thread-safe data structures
* Thread confinement fine-grained
* Thread confinement coarse-grained
* Mutual exclusion
* Actors

### Select Expression (experimental)

* Select Expression (experimental)
* Selecting on close
* Selecting to send
* Selecting deferred values
* Switch over a channel of deferred values

***

# Java Interop

* Calling Java from Kotlin
* Calling Kotlin from Java

***

# Core Libraries

* Standard Library
* kotlin.test

***

# Reference

* Keywords and Operators
* Grammar

***

# Eğitmen Hakkında

![Profil Fotoğrafı](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/bg_profile.PNG)

* **Gökhan ÖZTÜRK**, 17 Haziran 1990, İstanbul  doğumlu.
* Lise -> Nuri Cıngıllıoğlu "Süper" Lisesi (2004~2008 | Derece = 3.84/5)
* Lisans -> Maltepe Üniversitesi, Mühendislik ve Doğa Bilimleri Fakultesi, Yazılım Mühendisliği (2009-2013 | Derece 3.21/4)
* Yüksek Lisans -> Maltepe Üniversitesi, Fen Bilimleri Enstitüsü, Bilgisayar Mühendisliği Tezli Yüksek Lisansı (Tez aşamasında bıraktı. 2015-2018 | Derece 2.86/4)

### Ben Kimim?
Hırslı, araştırmacı, gelişime açık, mesleğine aşık, girişken ve konuşkan.

### Kim olmak istiyorum?
Belli bir yaşa kadar; mesleğime ilişkin teknik yetkinliğe ulaşıncaya kadar -işin mutfağında kalıp, sonrasında buradan aldığım teknik yeterlilikle, yazılım süreç yönetimlerine yoğunlaşmak. Bu süreç içerisinde işin mutfağındaki gruplara liderlik edebilmek.

### Topluluk için ek olarak neler yapıyorum?
Mesai dışı zamanlarımda ise gönüllü ve/veya ücretsiz eğitimlerle sosyal sorumluluk projelerine ve yazılım geliştirme topluluklarına katkı sunmaya çalışıyorum. 

### Deneyimler?
* Akbank ~ Nomad Commerce | Akbank Direkt Mobil -> Jr. Android Uygulama Geliştirme Uzmanı (Haz 2013 – Haz 2015)
* Akbank ~ Nomad Commerce | Akbank Direkt Mobil -> iOS & Android Takım Lideri (Haz 2015 – Mar 2017)
* Demirören Medya | Sonra Ne Oldu? & Milliyet -> Android Uygulama Geliştirme Uzmanı (Nis 2017 - Eyl 2018)
* Demirören Medya | Hurriyet & Milliyet -> Lead Android Uygulama Geliştirme Uzmanı (Eyl 2018 - Oca 2019)
* Turkcell ~ Ericsson | Yaani Browser -> Android Uygulama Geliştirme Uzmanı (Oca 2019 - Eyl 2019)
* Turkcell ~ Ericsson | Lifebox -> Lead Android Uygulama Geliştirme Uzmanı (Eyl 2019 - Devam)

***

### Yayın & İletişim Kanalları

[![Linkedin](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_linkedin.png)](https://www.linkedin.com/in/AndroidEduIO/)

[![Twitch](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_twitch.png)](https://www.twitch.tv/Codemy)
[![Youtube](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_youtube.png)](https://www.youtube.com/channel/UC7TQyu2rmAPzVNIF9nR176w)
[![Medium](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_medium.png)](https://Codemy.Live)
[![Discord](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_discord.png)](https://discord.gg/nDTD4TQ)

[![Twitter](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_twitter.png)](https://twitter.com/CodemyLive)
[![Instagram](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_instagram.png)](https://www.instagram.com/CodemyLive)
[![Facebook Sayfa](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_facebook_page.png)](https://www.facebook.com/CodemyLive)
[![Facebook Grup](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_facebook_group.png)](https://www.facebook.com/groups/CodemyLive)

***

### Geri Bildirim için Tıklayın <3
[![Mail](https://github.com/CodemyLive/Git-GitHub-Syllabus/blob/master/assets/ic_mail.png)](mailto:GokhanOzturk@AndroidEdu.IO)

***

Code with ❤️
