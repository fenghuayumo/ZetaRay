set(RP_PRE_LIGHTING_DIR ${ZETA_RENDER_PASS_DIR}/PreLighting)
set(RP_PRE_LIGHTING_SRC
    ${RP_PRE_LIGHTING_DIR}/BuildLightVoxelGrid.hlsl
    ${RP_PRE_LIGHTING_DIR}/EstimateTriEmissivePower.hlsl
	${RP_PRE_LIGHTING_DIR}/PreLighting.cpp
    ${RP_PRE_LIGHTING_DIR}/PreLighting.h
    ${RP_PRE_LIGHTING_DIR}/PreLighting_Common.h
    ${RP_PRE_LIGHTING_DIR}/PresampleEmissives.hlsl)
set(RP_PRE_LIGHTING_SRC ${RP_PRE_LIGHTING_SRC} PARENT_SCOPE)