Library Orchestration
========================

* **GIT repository:** `GitHub <https://github.com/8thlab/tracker-sdk-android>`_
* **CI system:**  Travis CI 

			.. image:: https://travis-ci.org/8thlab/tracker-sdk-android.svg?branch=master
						:target: https://travis-ci.org/8thlab/tracker-sdk-android
* **Maven reposiotry:** `Sonatype OSS <https://oss.sonatype.org/content/repositories/snapshots/com/8thlab/trackersdk/>`_


Publication flow:
----------------------

* **SNAPSHOT:**

	#. GIT Commit 
	#. Green Travis CI Build 
	#. Snapshot Version publication to OSS repository

* **RELEASE:**
	

	#. Green local build
	#. Version change

		#. Git Tag
		#. Version update in version file

	#. Publication
	
		#. Push release to GitHub
		#. Release version publication

	#. Promote version to maven central
