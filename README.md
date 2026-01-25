
# RMPFF (Roblox-Max-Preformance-FFlags)

Roblox FFlag config for the best preformance and fps that i have made this most likely isnt the best FFlag config that is out there but its good
if you want to remove things from the config then you can if there are any issues feel free to go to the issue tab and report the issue


## What each FFlag is doing


## vulkan (might not work on some devices not sure)
    "FFlagDebugGraphicsDisableDirect3D11": true,
    "FFlagDebugGraphicsPreferVulkan": true,

## hyperthreading (if cpu supports)
    "FFlagDebugCheckRenderThreading": true,
    "FFlagRenderDebugCheckThreading2": true,

## max threads
    "FIntRuntimeMaxNumOfThreads": 2400,

## smoother terain
    "FFlagDebugRenderingSetDeterministic": true,

## low quality terain textures
    "FIntTerrainArraySliceSize": 4,

## disable shadows
    "FIntRenderShadowIntensity": 0,

## disable wind (i dont know what this dose)
    "FFlagGlobalWindRendering": false,
    "FFlagGlobalWindActivated": false,

## limit light updates
    "FIntRenderLocalLightUpdatesMax": 8,
    "FIntRenderLocalLightUpdatesMin": 6,

## disable post fx
    "FFlagDisablePostFx": true,

## grey sky (only works to games with the default sky box)
    "FFlagDebugSkyGray": true,

## gpu light culling
    "FFlagFastGPULightCulling3": true,

## low quality textures

    "DFIntPerformanceControlTextureQualityBestUtility": -1,

## no avitar textures

    "DFIntTextureCompositorActiveJobs": 0,
    
## remove grass

    "FIntFRMMinGrassDistance": 0,
    "FIntFRMMaxGrassDistance": 0,
    "FIntRenderGrassDetailStrands": 0,
    "FIntRenderGrassHeightScaler": 0
    
