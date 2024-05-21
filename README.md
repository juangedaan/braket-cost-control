# Braket Cost Control

![image](https://github.com/juangedaan/braket-cost-tracker/assets/6960588/bd66e645-0ba6-4426-ab68-9064da10c3d1)

Amazon Braket provides access to quantum computers, managed simulators that simulate quantum circuits, and managed notebook development environments. There are two main pricing components when using a quantum computer, or quantum processing unit (QPU), on Amazon Braket: a per-shot fee and a per-task fee.

With this notebook customers can use the AWS Price List Service API to obtain all the relevant pricing information for Amazon Braket. They can use the AWS Price List Service to build cost control and scenario planning tools, reconcile billing data, forecast future spend for budgeting purposes, and provide cost benefit analysis that compare their internal workloads with Amazon Web Services.

The initial version does not contemplate the cost of ancilliary services like Amazon S3 for results storage, Sagemaker notebooks runtime, AWS CloudWatch for alarm management, or EventBridge for reactive triggers based on events.
