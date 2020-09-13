# blueline-factory-2020.09.11.04
any idea to help me to fix pls? 

#!/bin/shx


	# Copyright 2012 The Android Open Source Project
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
        ./fastboot flash bootloader bootloader-blueine-b11-0.2-6374987.img
        ./fastboot reboot-bootloader
        sleep 5
        ./fastboot flash radio radio-blueline-g845-00107-200409-b-6382632.img
        ./fastboot reboot-bootloader
        sleep 5
        ./fastboot -w update image-blueline-2020.09.11.14.zip
