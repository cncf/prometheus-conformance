-- **DRAFT** --

-- **TO BE APPROVED BY CNCF GB** --

# Prometheus Conformance

Prometheus is the standard for metric monitoring in the cloud native space and beyond. To ensure interoperability, to protect users from suprises, and to enable more parallel innovation, the Prometheus project is certifying subcomponent compliance and Prometheus compatibility.

## Updates to the Conformance Program
This conformance program will evolve over time as we find time to document, specify, and test current behaviour and as the functionality of Prometheus itself evolves. If you want to contribute ideas to improve, extend, or update the conformance process, you are welcome to propose your desired changes by creating issues in the [prometheus/compliance](https://github.com/prometheus/compliance) repository.

## Applying for Conformance Certification
All vendors are invited to submit conformance testing results for review and certification by the CNCF, which formally certifies conformant implementations.

## Benefits of Certification

In addition to providing confidence to end users of your Prometheus compatibility, offerings that certify are able to:

* Display the new Prometheus Compatibility logo mark on their marketing materials
* Use Prometheus in their product name by taking advantage of a new combination trademark rule the CNCF adopted for Prometheus Compatible projects and products

# Certification

The tests can be found in [prometheus/compliance](https://github.com/prometheus/compliance).

## Recertification

Certification of conformance is valid for 12 weeks or two minor Prometheus releases, whichever is longer. This should allow all projects and vendors enough time to update while being current and useful for users.

## Certification Types

There are two types of conformance certification:

## Subcomponent Compliance

Subcomponents carry their own test suite. Compliance is calculated as a percentage based on the tests and checklists in the relevant directories. When 100% compliance has been reached, a timestamped mark "foo YYYY-MM compliant", e.g. "PromQL 2021-04 compliant" will be awarded. 

Currently, there are three compliance tests:

* [OpenMetrics](https://github.com/prometheus/compliance/tree/main/openmetrics)
* [PromQL](https://github.com/prometheus/compliance/tree/main/promql)
* [Remote Write](https://github.com/prometheus/compliance/tree/main/remote_write)

## Prometheus Compatibility

All relevant compliance scores are multiplied into a compatibility score. When 100% compatibility has been reached, a versioned mark "Prometheus X.Y Compatible" will be awarded. 
