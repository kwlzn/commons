# ==================================================================================================
# Copyright 2011 Twitter, Inc.
# --------------------------------------------------------------------------------------------------
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this work except in compliance with the License.
# You may obtain a copy of the License in the LICENSE file, or at:
#
#  http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ==================================================================================================

python_library(
  name = 'common',
  dependencies = [
    'src/python/twitter/common/collections',
    'src/python/twitter/common/config',
    'src/python/twitter/common/contextutil',
    'src/python/twitter/common/decorators',
    'src/python/twitter/common/dirutil',
    'src/python/twitter/common/exceptions',
    'src/python/twitter/common/lang',
    'src/python/twitter/common/log',
    'src/python/twitter/common/metrics',
    'src/python/twitter/common/options',
    'src/python/twitter/common/quantity',
    'src/python/twitter/common/string',
    'src/python/twitter/common/util',
  ],
  provides = setup_py(
    name = 'twitter.common-core',
    version = '0.1.0',
    description = "Twitter's core Python libraries.",
    url = 'https://github.com/twitter/commons',
    license = 'Apache License, Version 2.0',
    zip_safe = True,
    classifiers = [
      'Intended Audience :: Developers',
      'License :: OSI Approved :: Apache Software License',
      'Operating System :: OS Independent',
      'Programming Language :: Python',
    ]
  )
)
