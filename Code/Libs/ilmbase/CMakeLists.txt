#START-FILE-LIST
# File List auto generated by waf2cmake.py, do not modify manually.

start_sources()
# -- ilmbase.waf_files --
sources_platform(WIN32)
add_sources("NoUberFile"
	PROJECTS ilmbase
	SOURCE_GROUP "Configuration"
	    "${SDK_DIR}/ilmbase/config.windows/IlmBaseConfig.h"

	SOURCE_GROUP "IlmThread"
	    "${SDK_DIR}/ilmbase/IlmThread/IlmThreadMutexWin32.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadSemaphoreWin32.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadWin32.cpp"
	)

sources_platform(LINUX)
add_sources("NoUberFile"
	PROJECTS ilmbase
	SOURCE_GROUP "Configuration"
	    "${SDK_DIR}/ilmbase/config/IlmBaseConfig.h"
		)

sources_platform(ALL)
add_sources("NoUberFile"
	PROJECTS ilmbase
	SOURCE_GROUP "Half"
		"${SDK_DIR}/ilmbase/Half/half.cpp"
		"${SDK_DIR}/ilmbase/Half/half.h"
		"${SDK_DIR}/ilmbase/Half/halfExport.h"
		"${SDK_DIR}/ilmbase/Half/halfFunction.h"
		"${SDK_DIR}/ilmbase/Half/halfLimits.h"
		"eLut.h"
		"toFloat.h"
	SOURCE_GROUP "Iex"
		"${SDK_DIR}/ilmbase/Iex/IexBaseExc.cpp"
		"${SDK_DIR}/ilmbase/Iex/IexThrowErrnoExc.cpp"
		"${SDK_DIR}/ilmbase/Iex/IexBaseExc.h"
		"${SDK_DIR}/ilmbase/Iex/IexMathExc.h"
		"${SDK_DIR}/ilmbase/Iex/IexThrowErrnoExc.h"
		"${SDK_DIR}/ilmbase/Iex/IexErrnoExc.h"
		"${SDK_DIR}/ilmbase/Iex/IexMacros.h"
		"${SDK_DIR}/ilmbase/Iex/Iex.h"
		"${SDK_DIR}/ilmbase/Iex/IexNamespace.h"
		"${SDK_DIR}/ilmbase/Iex/IexExport.h"
		"${SDK_DIR}/ilmbase/Iex/IexForward.h"
	SOURCE_GROUP "IexMath"
		"${SDK_DIR}/ilmbase/IexMath/IexMathFloatExc.cpp"
		"${SDK_DIR}/ilmbase/IexMath/IexMathFpu.cpp"
		"${SDK_DIR}/ilmbase/IexMath/IexMathFloatExc.h"
		"${SDK_DIR}/ilmbase/IexMath/IexMathFpu.h"
		"${SDK_DIR}/ilmbase/IexMath/IexMathIeeeExc.h"
	SOURCE_GROUP "IlmThread"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThread.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadMutex.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadMutexPosix.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadPool.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadPosix.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadSemaphore.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadSemaphorePosixCompat.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadSemaphorePosix.cpp"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThread.h"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadPool.h"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadSemaphore.h"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadMutex.h"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadNamespace.h"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadExport.h"
		"${SDK_DIR}/ilmbase/IlmThread/IlmThreadForward.h"
	SOURCE_GROUP "Imath"
		"${SDK_DIR}/ilmbase/Imath/ImathBox.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathRandom.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathColorAlgo.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathShear.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathFun.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathVec.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathMatrixAlgo.cpp"
		"${SDK_DIR}/ilmbase/Imath/ImathBoxAlgo.h"
		"${SDK_DIR}/ilmbase/Imath/ImathBox.h"
		"${SDK_DIR}/ilmbase/Imath/ImathColorAlgo.h"
		"${SDK_DIR}/ilmbase/Imath/ImathColor.h"
		"${SDK_DIR}/ilmbase/Imath/ImathEuler.h"
		"${SDK_DIR}/ilmbase/Imath/ImathExc.h"
		"${SDK_DIR}/ilmbase/Imath/ImathExport.h"
		"${SDK_DIR}/ilmbase/Imath/ImathForward.h"
		"${SDK_DIR}/ilmbase/Imath/ImathFrame.h"
		"${SDK_DIR}/ilmbase/Imath/ImathFrustum.h"
		"${SDK_DIR}/ilmbase/Imath/ImathFrustumTest.h"
		"${SDK_DIR}/ilmbase/Imath/ImathFun.h"
		"${SDK_DIR}/ilmbase/Imath/ImathGL.h"
		"${SDK_DIR}/ilmbase/Imath/ImathGLU.h"
		"${SDK_DIR}/ilmbase/Imath/ImathHalfLimits.h"
		"${SDK_DIR}/ilmbase/Imath/ImathInt64.h"
		"${SDK_DIR}/ilmbase/Imath/ImathInterval.h"
		"${SDK_DIR}/ilmbase/Imath/ImathLimits.h"
		"${SDK_DIR}/ilmbase/Imath/ImathLineAlgo.h"
		"${SDK_DIR}/ilmbase/Imath/ImathLine.h"
		"${SDK_DIR}/ilmbase/Imath/ImathMath.h"
		"${SDK_DIR}/ilmbase/Imath/ImathMatrixAlgo.h"
		"${SDK_DIR}/ilmbase/Imath/ImathMatrix.h"
		"${SDK_DIR}/ilmbase/Imath/ImathNamespace.h"
		"${SDK_DIR}/ilmbase/Imath/ImathPlane.h"
		"${SDK_DIR}/ilmbase/Imath/ImathPlatform.h"
		"${SDK_DIR}/ilmbase/Imath/ImathQuat.h"
		"${SDK_DIR}/ilmbase/Imath/ImathRandom.h"
		"${SDK_DIR}/ilmbase/Imath/ImathRoots.h"
		"${SDK_DIR}/ilmbase/Imath/ImathShear.h"
		"${SDK_DIR}/ilmbase/Imath/ImathSphere.h"
		"${SDK_DIR}/ilmbase/Imath/ImathVecAlgo.h"
		"${SDK_DIR}/ilmbase/Imath/ImathVec.h"
)

# -- eLut.waf_files --
sources_platform(ALL)
add_sources("NoUberFile"
	PROJECTS eLut
	SOURCE_GROUP "Root"
		"${SDK_DIR}/ilmbase/Half/eLut.cpp"
)

# -- toFloat.waf_files --
sources_platform(ALL)
add_sources("NoUberFile"
	PROJECTS toFloat
	SOURCE_GROUP "Root"
		"${SDK_DIR}/ilmbase/Half/toFloat.cpp"
)

end_sources()
#END-FILE-LIST

set(DEFAULT_DEFINITIONS "")
if (WIN32)
	set(DISABLE_WARNINGS /W0)  # Disable warnings from 3rdParty code.
	set(DEFAULT_DEFINITIONS "-D_HAS_EXCEPTIONS=0")
	set(CONFIG_DIR "${SDK_DIR}/ilmbase/config.windows")
else()
	set(DISABLE_WARNINGS -w)
	set(CONFIG_DIR "${SDK_DIR}/ilmbase/config")
endif()

CryEngineStaticModule(ilmbase SOLUTION_FOLDER "Libs")
target_include_directories(${THIS_PROJECT} PRIVATE "${SDK_DIR}/ilmbase/Half" "${SDK_DIR}/ilmbase/Iex" "${SDK_DIR}/ilmbase/IexMath" "${SDK_DIR}/ilmbase/Imath" ${CONFIG_DIR} )
target_compile_definitions(${THIS_PROJECT} PRIVATE -DNOMINMAX)
if (WIN32)
	target_compile_options(${THIS_PROJECT} PRIVATE ${DISABLE_WARNINGS} /GR /EHsc)  # Enable exceptions.
else()
	target_compile_options(${THIS_PROJECT} PRIVATE ${DISABLE_WARNINGS} -fexceptions) # Enable exceptions.
endif()
target_compile_options(${THIS_PROJECT} PRIVATE ${DEFAULT_FLAGS} )
target_include_directories(${THIS_PROJECT} INTERFACE "${SDK_DIR}/ilmbase/Half" "${SDK_DIR}/ilmbase/Iex" "${SDK_DIR}/ilmbase/IexMath" "${SDK_DIR}/ilmbase/Imath" ${CONFIG_DIR} )

# Tool to create toFloat.h
CryConsoleApplication(toFloat SOLUTION_FOLDER "Tools/ilm")
target_compile_options(${THIS_PROJECT} PRIVATE ${DISABLE_WARNINGS} )
target_compile_definitions(${THIS_PROJECT} PRIVATE ${DEFAULT_DEFINITIONS})

# Tool to create eLut.h
CryConsoleApplication(eLut SOLUTION_FOLDER "Tools/ilm")
target_compile_options(${THIS_PROJECT} PRIVATE ${DISABLE_WARNINGS} )
target_compile_definitions(${THIS_PROJECT} PRIVATE ${DEFAULT_DEFINITIONS})

