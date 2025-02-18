# Copyright 2019 The TensorFlow Lattice Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ==============================================================================

licenses(["notice"])

package(
    default_visibility = [
        "//tensorflow_lattice:__subpackages__",
    ],
)

py_binary(
    name = "canned_estimators_uci_heart",
    srcs = ["canned_estimators_uci_heart.py"],
    python_version = "PY3",
    deps = [
        # tensorflow dep,
        # tensorflow:tensorflow_compat_v1_estimator dep,
        # tensorflow:tensorflow_estimator dep,
        "//tensorflow_lattice",
    ],
)

py_binary(
    name = "keras_sequential_uci_heart",
    srcs = ["keras_sequential_uci_heart.py"],
    python_version = "PY3",
    deps = [
        # tensorflow dep,
        "//tensorflow_lattice",
    ],
)

py_binary(
    name = "keras_functional_uci_heart",
    srcs = ["keras_functional_uci_heart.py"],
    python_version = "PY3",
    deps = [
        # tensorflow dep,
        "//tensorflow_lattice",
    ],
)

py_binary(
    name = "custom_estimators_uci_heart",
    srcs = ["custom_estimators_uci_heart.py"],
    python_version = "PY3",
    deps = [
        # tensorflow dep,
        # tensorflow:tensorflow_compat_v1_estimator dep,
        # tensorflow:tensorflow_estimator dep,
        "//tensorflow_lattice",
    ],
)
