# essa-project (https://github.com/essa-project)
Elastic Stateful Serverless Architecture **[`essa-project`](https://github.com/essa-project)**.

Serverless computing has become increasingly popular because it simplifies the developer’s experience of constructing and deploying applications.
However, existing serverless FaaS (Function-as-a-Service) lacks state management, also it has high function invocation overhead (e.g. container based invocation)
Motivation for Essa-project is Elastic Stateful Serverless infrastructure:
- **[`Essa-RS`](https://github.com/essa-project/essa-rs)**: WebAssembly-based serverless function which is fast, polyglot (C/C++, Rust, etc languages), fully sandboxed (secure), less function invocation overhead
- Natively support efficient, consistent, and fault-tolerant state management thru **[`Anna-RS`](https://github.com/essa-project/anna-rs)** K/V store, which support low-latency, autoscaling and geo-distribution
- Geo-distributed middleware **[`Zenoh`](https://github.com/eclipse-zenoh)** to provide edge friendly deployment topology 
- Whole Rust language and WebAssembly software stack


