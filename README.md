# DDD and TDD Architecture With Flutter

This repository explain how to use TDD and DDD Architecture with Flutter.

**To use TDD, three directories were created .**

1.  [Interactions](test/interactions);
2.  [Unit](test/unit);
3.  [Widget](test/widget);

**To use DDD, some directories were created.**

* [Application](lib/application)
  * [Config](lib/application/config)
  * [Injections](lib/application/injections)
* [Data](lib/data)
  * [Dao](lib/data/dao)
  * [Resources](lib/data/resources)
    * [Database](lib/data/resources/database)
    * [Remote](lib/data/resources/remote)
* [Domain](lib/domain)
  * [Events](lib/domain/events)
  * [Managers](lib/domain/managers)
  * [States](lib/domain/states)
  * [Use Cases](lib/domain/use_cases)
* [Foundation](lib/foundation)
* [Presentation](lib/presentation)
  * [Routing](lib/presentation/routing)
  * [UI](lib/presentation/ui)
    * [Styles](lib/presentation/ui/styles)
    * [View](lib/presentation/ui/view)
    * [View Model](lib/presentation/ui/view_models)

**OBS.:** If you want more information about these directory, It is proposed that you enter them and read the readme, code examples and access bibliography's links.

## Bibliography

* [Clean Architecture — DDD for my Flutter, Spring and React projects - Maxime F.](https://mcssym.medium.com/clean-architecture-ddd-for-my-flutter-spring-and-react-projects-5be666f40ae2)
* [Flutter - Teste de Integração (Integration Test ou E2E Flutter) - Prof. Diego Antunes](https://www.youtube.com/watch?v=GEvNj7uogYE&ab_channel=Prof.DiegoAntunes)

 
