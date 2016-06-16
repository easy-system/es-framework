![Logo](data/es-logo.png?raw=true)

The framework of easy system.
=============================
The PHP web framework.

>In developing

Structure
=========


### External dependences
- [php-fig/http-message](https://github.com/php-fig/http-message)
  Holds all interfaces/classes/traits related to PSR-7.

### System Level 0, "Drivers"

| Component | Description |
| --- | --- |
| [easy-system/es-component](https://github.com/easy-system/es-component) | The package provides the interface of system component. |
| [easy-system/es-exception](https://github.com/easy-system/es-exception) | The package provides the interfaces of system exceptions. |
| [easy-system/es-container](https://github.com/easy-system/es-container) | The package provides the functionality of typical data containers. |
| [easy-system/es-loader](https://github.com/easy-system/es-loader)       | The package provides a loading of PHP classes. |
| [easy-system/es-http](https://github.com/easy-system/es-http)           | The package represents a HTTP layer, compatible with PSR-7. |
| [easy-system/es-cache](https://github.com/easy-system/es-cache)         | The package provides the data caching feature. |
| [easy-system/es-router](https://github.com/easy-system/es-router)       | The Psr-7 -compatible router. |
| easy-system/es-session | In developing |
| easy-system/es-dbal    | In developing |

### System Level I, "Kernel"

| Component | Description |
| --- | --- |
| [easy-system/es-services](https://github.com/easy-system/es-services) | The package provides a implementation of Service Locator design pattern. |
| [easy-system/es-events](https://github.com/easy-system/es-events)     | The package provides an implementation of event-driven architecture. |
| [easy-system/es-system](https://github.com/easy-system/es-system)     | The event based system. |
| [easy-system/es-modules](https://github.com/easy-system/es-modules)   | The package provides the functionality of modular system. |
| [easy-system/es-server](https://github.com/easy-system/es-server)     | The package provides exchange of HTTP messages with clients. |

### System Level II, MVC Layer

| Component | Description |
| --- | --- |
| [easy-system/es-mvc](https://github.com/easy-system/es-modules)                           | The package provides MVC layer interfaces. |
| [easy-system/es-controllers](https://github.com/easy-system/es-controllers)               | The package provides the implementation of MVC controllers in modular system. |
| [easy-system/es-controller-plugins](https://github.com/easy-system/es-controller-plugins) | The package provides the functionality of the controller plugins.
| [easy-system/es-view](https://github.com/easy-system/es-view)                             | The package provides the implementation of MVC view in modular system. |
| [easy-system/es-view-helpers](https://github.com/easy-system/es-view-helpers)             | The package provides the functionality of the view helpers.
| [easy-system/es-template](https://github.com/easy-system/es-template)                     | The default system template engine.
| easy-system/es-models       | In developing

### System Level III, System handlers

| Component | Description |
| --- | --- |
| [easy-system/es-routing](https://github.com/easy-system/es-routing)       | The package provides the routing of http request. |
| [easy-system/es-dispatcher](https://github.com/easy-system/es-dispatcher) | The package provides the dispatching of system controllers. |
| easy-system/es-finisher | In developing |
| easy-system/es-error    | In developing |

### System Level IV, Application layer

| Component | Description |
| --- | --- |
| easy-system/es-debug      | In developing |
| easy-system/es-database   | In developing |
| easy-system/es-navigation | In developing |

