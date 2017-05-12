Introduction
Atlas is accompanied by the continuous development of mobile phones Taobao derived from a running on the Android system, a containerized framework, we also called dynamic component (Dynamic Bundle) framework. It mainly provides decoupling, component, and dynamic support. Covering the engineers of the project coding period, Apk operation and follow-up maintenance of the various problems.

* In the project period, to achieve the independent development of the project, debugging functions, engineering modules can be independent.

* At run time, to achieve a complete component life cycle mapping, class isolation and other mechanisms.

* In the operation and maintenance period, to provide rapid incremental update repair capacity, fast upgrade.

Atlas is the framework for the engineering and operational phases, and we try to put some work into engineering, which ensures that the runtime is simpler and more stable.

Compared to multidex, atlas, while resolving the number of methods, uses OSGI as a reference to clarify the boundaries of business development, enabling the business to flexibly publish, dynamically update, and provide an online fault while satisfying parallel iterations and rapid development Quick fix ability.

And some plug-ins framework is different, atlas is a component framework, atlas is not a multi-process framework, he is mainly in the running environment on demand to complete the installation of the bundle, load classes and resources.
