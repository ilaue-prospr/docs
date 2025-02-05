---
id: set-up-espidf
title: Set up ESP-IDF for ESP32
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

The [Golioth Firmware SDK](https://github.com/golioth/golioth-firmware-sdk) can be
installed as a component of the ESP-IDF. This delivers a set of APIs that let
you use Golioth with any ESP-IDF based projects. This guide will walk through
the process of installing both the ESP-IDF and the Golioth Firmware SDK.

### Install ESP-IDF

import SetupEspIdf from '/docs/partials/espidf/install-espidf.md'

<SetupEspIdf/>

### Install Golioth Firmware SDK

import InstallFirmwareSDK from '/docs/partials/espidf/install-golioth-firmware-sdk.md'

<InstallFirmwareSDK/>

### Set the ESP IDF environment variables

import InstallEspIdfEnv from '/docs/partials/espidf/install-espidf-environment.md'

<InstallEspIdfEnv/>

### Sample build

import SampleBuild from '/docs/partials/espidf/install-sample-build.md'

<SampleBuild />
