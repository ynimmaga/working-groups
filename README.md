<!--- SPDX-License-Identifier: Apache-2.0 -->

# Working Groups

As described in the ONNX [governance](https://github.com/onnx/onnx/tree/main/community#wg---working-groups), Working Groups (WGs) are temporary groups formed to address issues that cross SIG boundaries. Working Groups have a have a clear goal measured through specific deliverables and disband after the goal is achieved. Working groups do not own artifacts long term; they create specifications, recommendations, and/or code implementations for submission to the relevant SIGs for approval and acceptance.

## Proposing a new working group
New Working Groups are created when there is sufficient interest in a topic area and someone volunteers to be the chair for the group and submits a proposal to the steering committee. The chair facilitates the discussion and helps synthesize proposals and decisions.

## Joining a working group
Working Groups have their discussions on Slack in dedicated channels. (Older working groups used Gitter rooms which are now archived)

You can find the schedule of meetings on the [LF AI wiki](https://wiki.lfai.foundation/pages/viewpage.action?pageId=18481196)

Working Groups store these artifacts, including meeting notes, in this repository. The working group leads have merge permissions on the repo but should only handle PRs related to their working group.

## Active working groups

Contact e-mail addresses of WG leads can be found [here](https://wiki.lfaidata.foundation/pages/viewpage.action?pageId=18481196).

| Working Group      | Objectives    |
| ------------------ | ------------- |
| [Preprocessing](https://lfaifoundation.slack.com/archives/C02AANGFBJB) | Data pre/post processing and featurization |
| [Multi-device](https://lfaifoundation.slack.com/archives/C05JY32GCCS)  | Multi-device support in ONNX               |
| Safety-Related-Profile | |
| [Generative-AI](https://lfaifoundation.slack.com/archives/C08MERYU84T) | Accelerate GenAI support in ONNX |

## Completed working groups

| Working Group      | Objectives    | Status |
| ------------------ | ------------- | ------ |
| [Release](https://lfaifoundation.slack.com/archives/C018VGGJUGK) | Improve and document release process, enhance release verification, identify fixes for release builds, recommend release operational guidelines in communication, frequency, scope, dependencies, and schedule | Completed - release process enhanced and documented at https://github.com/onnx/onnx/blob/main/docs/OnnxReleases.md
| [Control Flow and Loops](https://gitter.im/onnx/ControlFlowWG) | Enable dynamic control structures to enable advanced models for NLP, speech, and video/image processing | Completed - If, Loop, and Scan operators were added in ONNX 1.3 release. |
| Quantization | Enhance ONNX to support quantized data types and operators on a variety of runtimes and hardware devices | Completed - added in ONNX 1.5 release. |
| Foundation | Identify and evaluate non-profit foundation options for the ONNX consortium.  Execute on best option. | Completed - ONNX joined LF AI in November 2019|

## Inactive working groups

| Working Group      | Objectives    | Status |
| ------------------ | ------------- | ------ |
| Testing/Compliance | Create tools, tests and APIs to ensure models and backends comply with the ONNX specification | became part of the ArchInfra SIG for now |
| Edge/Mobile | Enable deployment of ONNX models to edge platforms by identifying the ONNX operators that must be supported by mobile and IoT runtimes, defining tool chain requirements, and contributing to ONNX compatibility tests | Stopped as of January 2020 |
| Data Pipelines | Define new operators for processing the data that goes in and comes out | No recent activity |
| [Training](https://lfaifoundation.slack.com/archives/C018K560U14) | Expand ONNX to support training as well as inference |
