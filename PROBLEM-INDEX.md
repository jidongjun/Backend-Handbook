# Backend Interview Bible

> Java Backend Interview Handbook
>
> Total: 450 Problems

---

## 상태

|기호|의미|
|---|---|
|⬜|미작성|
|🟨|초안|
|🟩|완료|
|🔁|수정 필요|
|⭐|즐겨찾기|
|❓|복습|

---

# 01. Java Core (001~050)

| 상태  | 번호  | 주제                            | 난이도 | 출제     | 예상  |
| --- | --- | ----------------------------- | --- | ------ | --- |
| 🟨  | 001 | Java Architecture             | ⭐   | 🔥🔥   | 20m |
| 🟨  | 002 | JVM vs JRE vs JDK             | ⭐   | 🔥🔥🔥 | 20m |
| 🟨  | 003 | Java Compilation Process      | ⭐⭐  | 🔥🔥   | 30m |
| 🟨  | 004 | Class File & Bytecode         | ⭐⭐  | 🔥🔥   | 30m |
| 🟨  | 005 | Object Class                  | ⭐   | 🔥🔥🔥 | 20m |
| 🟨  | 006 | String                        | ⭐⭐  | 🔥🔥🔥 | 40m |
| 🟨   | 007 | String Pool                   | ⭐⭐⭐ | 🔥🔥🔥 | 40m |
| ⬜   | 008 | StringBuilder vs StringBuffer | ⭐⭐  | 🔥🔥   | 30m |
| ⬜   | 009 | equals() & hashCode()         | ⭐⭐⭐ | 🔥🔥🔥 | 60m |
| ⬜   | 010 | == vs equals()                | ⭐⭐  | 🔥🔥🔥 | 20m |

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|011|Immutable Object|⭐⭐|🔥🔥🔥|40m|
|⬜|012|Wrapper Class|⭐⭐|🔥🔥|30m|
|⬜|013|Auto Boxing & Unboxing|⭐⭐|🔥🔥|20m|
|⬜|014|Enum|⭐⭐|🔥🔥|30m|
|⬜|015|Generic|⭐⭐⭐|🔥🔥🔥|60m|
|⬜|016|PECS (Producer Extends Consumer Super)|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|017|Annotation|⭐⭐|🔥🔥|30m|
|⬜|018|Reflection|⭐⭐⭐|🔥🔥🔥|60m|
|⬜|019|Exception|⭐⭐|🔥🔥🔥|40m|
|⬜|020|Checked vs Unchecked Exception|⭐⭐|🔥🔥🔥|40m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|021|try-with-resources|⭐⭐|🔥🔥|20m|
|⬜|022|Collection Framework|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|023|List Interface|⭐|🔥🔥|20m|
|⬜|024|Set Interface|⭐|🔥🔥|20m|
|⬜|025|Map Interface|⭐⭐|🔥🔥🔥|30m|
|⬜|026|ArrayList|⭐⭐⭐|🔥🔥🔥|60m|
|⬜|027|LinkedList|⭐⭐⭐|🔥🔥🔥|60m|
|⬜|028|Vector|⭐⭐|🔥|20m|
|⬜|029|HashSet|⭐⭐⭐|🔥🔥|40m|
|⬜|030|TreeSet|⭐⭐⭐|🔥🔥|40m|

| 상태  | 번호  | 주제                              | 난이도   | 출제     | 예상  |
| --- | --- | ------------------------------- | ----- | ------ | --- |
| ⬜   | 031 | HashMap                         | ⭐⭐⭐⭐  | 🔥🔥🔥 | 90m |
| ⬜   | 032 | Hash Function                   | ⭐⭐⭐   | 🔥🔥   | 40m |
| ⬜   | 033 | Hash Collision                  | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 034 | HashMap Resize                  | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 035 | Treeification (Red-Black Tree)  | ⭐⭐⭐⭐  | 🔥🔥   | 50m |
| ⬜   | 036 | Hashtable vs HashMap            | ⭐⭐⭐   | 🔥🔥   | 40m |
| ⬜   | 037 | ConcurrentHashMap               | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
| ⬜   | 038 | Iterator                        | ⭐⭐    | 🔥🔥   | 30m |
| ⬜   | 039 | Fail-Fast vs Fail-Safe Iterator | ⭐⭐⭐⭐  | 🔥🔥🔥 | 50m |
| ⬜   | 040 | Comparable vs Comparator        | ⭐⭐⭐   | 🔥🔥🔥 | 40m |

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|041|Queue Interface|⭐⭐|🔥🔥|20m|
|⬜|042|Deque|⭐⭐|🔥|20m|
|⬜|043|PriorityQueue|⭐⭐⭐|🔥🔥|40m|
|⬜|044|Stack vs Deque|⭐⭐|🔥|20m|
|⬜|045|Lambda Expression|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|046|Functional Interface|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|047|Method Reference|⭐⭐|🔥🔥|20m|
|⬜|048|Stream API|⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|049|Optional|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|050|Serialization & Serializable|⭐⭐⭐|🔥🔥|40m|
# 02. Concurrency & Spring Core (051~100)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|051|Process vs Thread|⭐⭐|🔥🔥🔥|40m|
|⬜|052|Thread Lifecycle|⭐⭐|🔥🔥|30m|
|⬜|053|Thread Creation (extends vs Runnable)|⭐⭐|🔥🔥|30m|
|⬜|054|Callable & Future|⭐⭐⭐|🔥🔥|40m|
|⬜|055|Future vs CompletableFuture|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|056|Executor Framework|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|057|ExecutorService|⭐⭐⭐|🔥🔥|40m|
|⬜|058|Thread Pool|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|059|ForkJoinPool|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|060|Virtual Thread (Java 21)|⭐⭐⭐⭐|🔥🔥🔥|70m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|061|Race Condition|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|062|Critical Section|⭐⭐⭐|🔥🔥|30m|
|⬜|063|Thread Safety|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|064|volatile|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|065|synchronized|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|066|Monitor Lock|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|067|Intrinsic Lock|⭐⭐⭐|🔥🔥|40m|
|⬜|068|ReentrantLock|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|069|ReadWriteLock|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|070|StampedLock|⭐⭐⭐⭐⭐|🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|071|CAS (Compare-And-Swap)|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|072|Atomic Classes|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|073|Unsafe Class|⭐⭐⭐⭐⭐|🔥🔥|60m|
|⬜|074|AQS (AbstractQueuedSynchronizer)|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|075|CountDownLatch|⭐⭐⭐|🔥🔥|40m|
|⬜|076|CyclicBarrier|⭐⭐⭐|🔥🔥|40m|
|⬜|077|Semaphore|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|078|BlockingQueue|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|079|Producer Consumer Pattern|⭐⭐⭐|🔥🔥|40m|
|⬜|080|Deadlock & Livelock|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|081|Spring Framework Architecture|⭐⭐|🔥🔥🔥|40m|
|⬜|082|IoC (Inversion of Control)|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|083|DI (Dependency Injection)|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|084|Bean Lifecycle|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|085|ApplicationContext vs BeanFactory|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|086|Component Scan|⭐⭐⭐|🔥🔥|40m|
|⬜|087|Bean Scope|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|088|Configuration Class|⭐⭐⭐|🔥🔥|40m|
|⬜|089|@Bean vs @Component|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|090|Bean Post Processor|⭐⭐⭐⭐|🔥🔥|60m|

| 상태  | 번호  | 주제                            | 난이도  | 출제     | 예상  |
| --- | --- | ----------------------------- | ---- | ------ | --- |
| ⬜   | 091 | Spring AOP                    | ⭐⭐⭐⭐ | 🔥🔥🔥 | 70m |
| ⬜   | 092 | Proxy Pattern                 | ⭐⭐⭐⭐ | 🔥🔥🔥 | 60m |
| ⬜   | 093 | JDK Dynamic Proxy             | ⭐⭐⭐⭐ | 🔥🔥🔥 | 60m |
| ⬜   | 094 | CGLIB Proxy                   | ⭐⭐⭐⭐ | 🔥🔥🔥 | 60m |
| ⬜   | 095 | Advice / Pointcut / JoinPoint | ⭐⭐⭐⭐ | 🔥🔥   | 60m |
| ⬜   | 096 | Spring Event                  | ⭐⭐⭐  | 🔥🔥   | 40m |
| ⬜   | 097 | ApplicationEventPublisher     | ⭐⭐⭐  | 🔥🔥   | 40m |
| ⬜   | 098 | Resource Loading              | ⭐⭐   | 🔥     | 30m |
| ⬜   | 099 | Environment & PropertySource  | ⭐⭐⭐  | 🔥🔥   | 40m |
| ⬜   | 100 | Spring Core Summary Interview | ⭐⭐⭐⭐ | 🔥🔥🔥 | 60m |
# 03. Spring MVC & Spring Boot (101~150)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|101|Spring MVC Architecture|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|102|DispatcherServlet|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|103|Front Controller Pattern|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|104|HTTP Request Lifecycle|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|105|HandlerMapping|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|106|HandlerAdapter|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|107|Controller|⭐⭐|🔥🔥🔥|20m|
|⬜|108|RestController|⭐⭐|🔥🔥🔥|20m|
|⬜|109|RequestMapping|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|110|RequestParam vs PathVariable|⭐⭐|🔥🔥🔥|20m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|111|Model & ModelAndView|⭐⭐|🔥🔥|30m|
|⬜|112|HttpMessageConverter|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|113|ViewResolver|⭐⭐⭐|🔥🔥|40m|
|⬜|114|Content Negotiation|⭐⭐⭐|🔥🔥|40m|
|⬜|115|Data Binding|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|116|Formatter & Converter|⭐⭐⭐|🔥🔥|40m|
|⬜|117|Validation (Bean Validation)|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|118|BindingResult|⭐⭐⭐|🔥🔥|30m|
|⬜|119|@Valid vs @Validated|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|120|Multipart File Upload|⭐⭐⭐|🔥🔥|40m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|121|Filter|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|122|Interceptor|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|123|Filter vs Interceptor|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|124|Exception Handling|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|125|@ControllerAdvice|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|126|ResponseEntity|⭐⭐⭐|🔥🔥🔥|30m|
|⬜|127|REST API Design|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|128|API Versioning|⭐⭐⭐|🔥🔥|40m|
|⬜|129|CORS|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|130|File Download|⭐⭐⭐|🔥🔥|30m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|131|Spring Boot Architecture|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|132|SpringApplication|⭐⭐⭐|🔥🔥|30m|
|⬜|133|Auto Configuration|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|134|Spring Boot Starter|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|135|Conditional Annotation|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|136|ConfigurationProperties|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|137|application.yml|⭐⭐|🔥🔥|20m|
|⬜|138|Profile|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|139|External Configuration|⭐⭐⭐|🔥🔥|40m|
|⬜|140|Actuator|⭐⭐⭐⭐|🔥🔥🔥|60m|

| 상태  | 번호  | 주제                                  | 난이도  | 출제     | 예상  |
| --- | --- | ----------------------------------- | ---- | ------ | --- |
| ⬜   | 141 | Logging (SLF4J & Logback)           | ⭐⭐⭐  | 🔥🔥🔥 | 40m |
| ⬜   | 142 | Lombok                              | ⭐⭐   | 🔥🔥   | 20m |
| ⬜   | 143 | Spring DevTools                     | ⭐    | 🔥     | 10m |
| ⬜   | 144 | Spring Boot Test                    | ⭐⭐⭐  | 🔥🔥🔥 | 50m |
| ⬜   | 145 | MockMvc                             | ⭐⭐⭐  | 🔥🔥   | 40m |
| ⬜   | 146 | TestRestTemplate                    | ⭐⭐   | 🔥     | 20m |
| ⬜   | 147 | Swagger / OpenAPI                   | ⭐⭐⭐  | 🔥🔥🔥 | 40m |
| ⬜   | 148 | SpringDoc OpenAPI                   | ⭐⭐   | 🔥🔥   | 20m |
| ⬜   | 149 | Spring Boot Best Practices          | ⭐⭐⭐⭐ | 🔥🔥🔥 | 60m |
| ⬜   | 150 | Spring MVC & Boot Interview Summary | ⭐⭐⭐⭐ | 🔥🔥🔥 | 60m |
# 04. JPA · Hibernate · Database (151~200)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|151|JPA Architecture|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|152|ORM (Object Relational Mapping)|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|153|EntityManager|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|154|Persistence Context|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|155|Entity Lifecycle|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|156|1st Level Cache|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|157|Write Behind|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|158|Dirty Checking|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|159|Flush|⭐⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|160|Detach · Clear · Close|⭐⭐⭐⭐|🔥🔥|50m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|161|Entity Mapping|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|162|Primary Key Strategy|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|163|Sequence vs Identity|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|164|Association Mapping|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|165|OneToOne Mapping|⭐⭐⭐|🔥🔥|40m|
|⬜|166|OneToMany Mapping|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|167|ManyToOne Mapping|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|168|ManyToMany Mapping|⭐⭐⭐|🔥🔥|40m|
|⬜|169|Bidirectional Mapping|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|170|Cascade & Orphan Removal|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|171|Fetch Strategy|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|172|Lazy Loading|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|173|Eager Loading|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|174|N+1 Problem|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|175|Fetch Join|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|176|EntityGraph|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|177|JPQL|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|178|Criteria API|⭐⭐⭐|🔥|40m|
|⬜|179|QueryDSL|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|180|Native Query|⭐⭐⭐|🔥🔥|40m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|181|Spring Transaction|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|182|@Transactional|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|183|Propagation|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|184|Isolation Level|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|185|Read Only Transaction|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|186|Optimistic Lock|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|187|Pessimistic Lock|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|188|Version Column|⭐⭐⭐|🔥🔥|40m|
|⬜|189|OSIV(Open Session In View)|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|190|JPA Performance Tuning|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

| 상태  | 번호  | 주제                                  | 난이도   | 출제     | 예상  |
| --- | --- | ----------------------------------- | ----- | ------ | --- |
| ⬜   | 191 | Database Normalization              | ⭐⭐⭐   | 🔥🔥   | 40m |
| ⬜   | 192 | Index                               | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 80m |
| ⬜   | 193 | Clustered vs Non-Clustered Index    | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 194 | Execution Plan (EXPLAIN)            | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
| ⬜   | 195 | Query Optimizer                     | ⭐⭐⭐⭐  | 🔥🔥🔥 | 70m |
| ⬜   | 196 | MVCC                                | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
| ⬜   | 197 | Deadlock                            | ⭐⭐⭐⭐  | 🔥🔥🔥 | 70m |
| ⬜   | 198 | Database Connection Pool (HikariCP) | ⭐⭐⭐⭐  | 🔥🔥🔥 | 70m |
| ⬜   | 199 | JDBC vs JPA                         | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 200 | JPA & Database Interview Summary    | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
# 05. JVM · Network · Operating System (201~250)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|201|JVM Architecture|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|202|Runtime Data Area|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|203|Heap Memory|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|204|Stack Memory|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|205|Method Area & Metaspace|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|206|PC Register & Native Method Stack|⭐⭐⭐|🔥🔥|40m|
|⬜|207|ClassLoader|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|208|Class Loading Process|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|209|Bytecode Execution Engine|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|210|JIT Compiler|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|211|Garbage Collection Overview|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|212|GC Roots|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|213|Young / Old Generation|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|214|Minor GC vs Major GC vs Full GC|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|215|G1 GC|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|216|ZGC|⭐⭐⭐⭐⭐|🔥🔥|80m|
|⬜|217|Java Memory Model (JMM)|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|218|Happens-Before|⭐⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|219|Escape Analysis|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|220|JVM Performance Tuning|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|221|OSI 7 Layer|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|222|TCP vs UDP|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|223|TCP 3-Way / 4-Way Handshake|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|224|HTTP Basics|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|225|HTTP Method|⭐⭐⭐|🔥🔥🔥|30m|
|⬜|226|HTTP Status Code|⭐⭐⭐|🔥🔥🔥|30m|
|⬜|227|HTTPS & TLS|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|228|HTTP/2 vs HTTP/3|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|229|REST API Principles|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|230|GraphQL vs REST|⭐⭐⭐⭐|🔥🔥|50m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|231|Cookie vs Session|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|232|JWT Authentication|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|233|OAuth 2.0|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|234|WebSocket|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|235|Server-Sent Events (SSE)|⭐⭐⭐|🔥🔥|40m|
|⬜|236|DNS Resolution Process|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|237|Load Balancer (L4 vs L7)|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|238|Reverse Proxy (Nginx)|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|239|CDN|⭐⭐⭐|🔥🔥|40m|
|⬜|240|Network Performance Tuning|⭐⭐⭐⭐|🔥🔥|60m|

| 상태  | 번호  | 주제                                   | 난이도   | 출제     | 예상  |
| --- | --- | ------------------------------------ | ----- | ------ | --- |
| ⬜   | 241 | Process vs Thread (OS)               | ⭐⭐⭐   | 🔥🔥🔥 | 40m |
| ⬜   | 242 | Context Switching                    | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 243 | Virtual Memory                       | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 244 | Paging & Segmentation                | ⭐⭐⭐⭐  | 🔥🔥   | 60m |
| ⬜   | 245 | CPU Scheduling                       | ⭐⭐⭐⭐  | 🔥🔥   | 50m |
| ⬜   | 246 | System Call                          | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 247 | File I/O vs NIO                      | ⭐⭐⭐⭐  | 🔥🔥🔥 | 70m |
| ⬜   | 248 | select / poll / epoll                | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
| ⬜   | 249 | Linux Memory Management              | ⭐⭐⭐⭐⭐ | 🔥🔥   | 80m |
| ⬜   | 250 | JVM · Network · OS Interview Summary | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
# 06. System Design · Redis · Kafka (251~300)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|251|System Design Fundamentals|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|252|Scalability|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|253|Availability vs Reliability|⭐⭐⭐⭐|🔥🔥|40m|
|⬜|254|CAP Theorem|⭐⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|255|Consistency Models|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|256|Replication|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|257|Sharding|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|258|Partitioning Strategy|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|259|Consistent Hashing|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|260|Distributed Lock|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|261|Caching Strategy|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|262|Cache Aside Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|263|Write Through / Write Back|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|264|Cache Eviction|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|265|Cache Stampede|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|266|Redis Architecture|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|267|Redis Data Structure|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|268|Redis Persistence (RDB/AOF)|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|269|Redis Pub/Sub|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|270|Redis Cluster|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|271|Redis Sentinel|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|272|Distributed Session|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|273|Rate Limiter|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|274|Bloom Filter|⭐⭐⭐⭐⭐|🔥🔥|70m|
|⬜|275|Message Queue Basics|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|276|Kafka Architecture|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|277|Topic / Partition|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|278|Producer|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|279|Consumer Group|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|280|Offset Management|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|281|Kafka Rebalancing|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|282|Exactly Once Semantics|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|283|Idempotency|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|284|Outbox Pattern|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|285|CDC (Change Data Capture)|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|286|Debezium|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|287|Saga Pattern|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|288|CQRS|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|289|Event Sourcing|⭐⭐⭐⭐⭐|🔥🔥|90m|
|⬜|290|Distributed Transaction|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

| 상태  | 번호  | 주제                              | 난이도   | 출제     | 예상  |
| --- | --- | ------------------------------- | ----- | ------ | --- |
| ⬜   | 291 | API Gateway                     | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 292 | Service Discovery               | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m |
| ⬜   | 293 | Circuit Breaker                 | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 80m |
| ⬜   | 294 | Bulkhead Pattern                | ⭐⭐⭐⭐  | 🔥🔥   | 60m |
| ⬜   | 295 | Retry Pattern                   | ⭐⭐⭐⭐  | 🔥🔥🔥 | 50m |
| ⬜   | 296 | Timeout Strategy                | ⭐⭐⭐⭐  | 🔥🔥🔥 | 50m |
| ⬜   | 297 | Backpressure                    | ⭐⭐⭐⭐⭐ | 🔥🔥   | 70m |
| ⬜   | 298 | Observability                   | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 70m |
| ⬜   | 299 | OpenTelemetry                   | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 80m |
| ⬜   | 300 | System Design Interview Summary | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m |
# 07. DevOps · Architecture · Testing · Career (301~350)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|301|Docker Architecture|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|302|Docker Image vs Container|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|303|Docker Volume|⭐⭐⭐|🔥🔥|30m|
|⬜|304|Docker Network|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|305|Docker Compose|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|306|Multi-stage Build|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|307|Container Optimization|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|308|Kubernetes Architecture|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|309|Pod|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|310|Deployment vs StatefulSet|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|311|Service|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|312|Ingress|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|313|ConfigMap & Secret|⭐⭐⭐⭐|🔥🔥🔥|50m|
|⬜|314|Helm|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|315|GitHub Actions|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|316|Jenkins Pipeline|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|317|CI/CD Pipeline|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|318|Blue-Green Deployment|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|319|Canary Deployment|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|320|Rolling Update|⭐⭐⭐⭐|🔥🔥|50m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|321|Domain Driven Design (DDD)|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|322|Bounded Context|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|323|Aggregate|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|324|Hexagonal Architecture|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|325|Clean Architecture|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|326|Layered Architecture|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|327|Modular Monolith|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|328|Microservice Architecture|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|329|Spring Modulith|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|330|Design Patterns in Spring|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|331|JUnit 5|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|332|Mockito|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|333|Testcontainers|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|334|Integration Test|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|335|Contract Test|⭐⭐⭐⭐|🔥🔥|50m|
|⬜|336|Performance Test (JMeter/k6)|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|337|TDD|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|338|BDD|⭐⭐⭐|🔥🔥|40m|
|⬜|339|Code Review Best Practices|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|340|Technical Debt|⭐⭐⭐⭐|🔥🔥🔥|60m|

| 상태  | 번호  | 주제                               | 난이도   | 출제     | 예상   |
| --- | --- | -------------------------------- | ----- | ------ | ---- |
| ⬜   | 341 | Project Architecture Review      | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m  |
| ⬜   | 342 | Troubleshooting Case Study       | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m  |
| ⬜   | 343 | Performance Tuning Case Study    | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m  |
| ⬜   | 344 | Database Optimization Case Study | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m  |
| ⬜   | 345 | Concurrency Issue Case Study     | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m  |
| ⬜   | 346 | System Design Interview Practice | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 90m  |
| ⬜   | 347 | Behavioral Interview (STAR)      | ⭐⭐⭐⭐  | 🔥🔥🔥 | 60m  |
| ⬜   | 348 | Technical Leadership             | ⭐⭐⭐⭐  | 🔥🔥   | 60m  |
| ⬜   | 349 | Backend Career Roadmap           | ⭐⭐⭐   | 🔥🔥   | 40m  |
| ⬜   | 350 | Final Backend Interview Review   | ⭐⭐⭐⭐⭐ | 🔥🔥🔥 | 120m |
# 08. Design Patterns (351~400)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|🟨|351|Pattern vs Principle vs Architecture|⭐⭐⭐|🔥🔥🔥|40m|
|⬜|352|SOLID Principles|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|353|Creational Patterns Overview|⭐⭐⭐|🔥🔥|40m|
|⬜|354|Factory Method Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|355|Abstract Factory Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|356|Builder Pattern|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|357|Prototype Pattern|⭐⭐⭐|🔥🔥|40m|
|⬜|358|Singleton Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|359|Object Pool Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|360|Dependency Injection Pattern|⭐⭐⭐⭐|🔥🔥🔥|70m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|361|Structural Patterns Overview|⭐⭐⭐|🔥🔥|40m|
|⬜|362|Adapter Pattern|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|363|Bridge Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|364|Composite Pattern|⭐⭐⭐|🔥🔥|50m|
|⬜|365|Decorator Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|366|Facade Pattern|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|367|Flyweight Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|368|Behavioral Patterns Overview|⭐⭐⭐|🔥🔥|40m|
|⬜|369|Strategy Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|370|Template Method Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|371|Observer Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|372|Command Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|373|Chain of Responsibility Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|374|State Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|375|Mediator Pattern|⭐⭐⭐|🔥🔥|50m|
|⬜|376|Memento Pattern|⭐⭐⭐|🔥|40m|
|⬜|377|Visitor Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|378|Interpreter Pattern|⭐⭐⭐⭐|🔥|50m|
|⬜|379|Null Object Pattern|⭐⭐⭐|🔥🔥|40m|
|⬜|380|Specification Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|381|Repository Pattern|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|382|Unit of Work Pattern|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|383|Data Mapper Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|384|Active Record Pattern|⭐⭐⭐|🔥🔥|50m|
|⬜|385|Identity Map Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|386|Service Layer Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|387|Domain Model vs Transaction Script|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|388|DTO Pattern|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|389|Gateway Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|390|Mapper and Assembler Patterns|⭐⭐⭐|🔥🔥|50m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|391|Value Object Pattern|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|392|Domain Event Pattern|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|393|Event Notification vs Event-Carried State Transfer|⭐⭐⭐⭐⭐|🔥🔥|80m|
|⬜|394|Anti-Corruption Layer Pattern|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|395|Strangler Fig Pattern|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|396|Sidecar Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|397|Ambassador Pattern|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|398|Leader Election Pattern|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|399|Pattern Selection and Composition|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|
|⬜|400|Anti-Patterns and Refactoring Strategies|⭐⭐⭐⭐⭐|🔥🔥🔥|90m|

# 09. Algorithm & Coding Interview (401~450)

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|401|Time and Space Complexity Analysis|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|402|Amortized Analysis|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|403|Recursion and Call Stack|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|404|Divide and Conquer|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|405|Sorting Algorithm Trade-offs|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|406|Insertion and Selection Sort|⭐⭐|🔥🔥|40m|
|⬜|407|Merge Sort|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|408|Quick Sort|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|409|Heap Sort|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|410|Counting Sort and Radix Sort|⭐⭐⭐⭐|🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|411|Stable Sort and In-Place Sort|⭐⭐⭐|🔥🔥|50m|
|⬜|412|Binary Search and Boundary Conditions|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|413|Two Pointers|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|414|Sliding Window|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|415|Prefix Sum and Difference Array|⭐⭐⭐|🔥🔥|50m|
|⬜|416|Hash-Based Problem Solving|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|417|Fast and Slow Pointer Technique|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|418|Stack and Monotonic Stack|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|419|Monotonic Queue|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|420|Heap and Top-K Problems|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|421|Tree Traversal|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|422|Binary Search Tree Algorithms|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|423|Balanced Tree Operations|⭐⭐⭐⭐|🔥🔥|70m|
|⬜|424|Trie Algorithms|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|425|Graph Representation and Traversal Design|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|426|Breadth-First Search (BFS)|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|427|Depth-First Search (DFS)|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|428|Topological Sort|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|429|Union-Find|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|430|Dijkstra Algorithm|⭐⭐⭐⭐|🔥🔥🔥|70m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|431|Bellman-Ford Algorithm|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|432|Floyd-Warshall Algorithm|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|433|Minimum Spanning Tree|⭐⭐⭐⭐|🔥🔥|70m|
|⬜|434|Backtracking|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|435|Greedy Algorithms|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|436|Dynamic Programming Fundamentals|⭐⭐⭐⭐|🔥🔥🔥|70m|
|⬜|437|Knapsack Problems|⭐⭐⭐⭐|🔥🔥|70m|
|⬜|438|Longest Increasing Subsequence|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|439|Longest Common Subsequence|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|440|Interval Algorithms|⭐⭐⭐⭐|🔥🔥🔥|60m|

|상태|번호|주제|난이도|출제|예상|
|---|---|---|---|---|---|
|⬜|441|Bit Manipulation|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|442|KMP String Matching|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|443|Rabin-Karp and Rolling Hash|⭐⭐⭐⭐|🔥🔥|60m|
|⬜|444|Palindrome Algorithms|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|445|Matrix and Grid Traversal|⭐⭐⭐|🔥🔥🔥|50m|
|⬜|446|External Sorting for Large Data|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|447|Streaming Top-K and Heavy Hitters|⭐⭐⭐⭐⭐|🔥🔥🔥|80m|
|⬜|448|Parallel Algorithm Trade-offs|⭐⭐⭐⭐⭐|🔥🔥|80m|
|⬜|449|Coding Interview Testing Strategy|⭐⭐⭐⭐|🔥🔥🔥|60m|
|⬜|450|Backend Coding Interview Comprehensive Review|⭐⭐⭐⭐⭐|🔥🔥🔥|120m|
