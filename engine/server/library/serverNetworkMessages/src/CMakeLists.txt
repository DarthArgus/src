
set(SHARED_SOURCES
	shared/AvatarList.cpp
	shared/AvatarList.h
	shared/AvatarListArchive.cpp
	shared/AvatarListArchive.h
	shared/ChatConnectAvatar.cpp
	shared/ChatConnectAvatar.h
	shared/ChatDisconnectAvatar.cpp
	shared/ChatDisconnectAvatar.h
	shared/ChatServerOnline.cpp
	shared/ChatServerOnline.h
	shared/EnumerateServers.cpp
	shared/EnumerateServers.h
	shared/RandomName.cpp
	shared/RandomName.h
	shared/TaskConnectionIdMessage.cpp
	shared/TaskConnectionIdMessage.h
	shared/TaskEnumCluster.cpp
	shared/TaskEnumCluster.h
	shared/TaskEnumProcesses.cpp
	shared/TaskEnumProcesses.h
	shared/TaskKillProcess.cpp
	shared/TaskKillProcess.h
	shared/TaskSpawnProcess.cpp
	shared/TaskSpawnProcess.h
	shared/TaskSpawnProcessAck.cpp
	shared/TaskSpawnProcessAck.h
	shared/TaskUtilization.cpp
	shared/TaskUtilization.h
	shared/VerifyAndLockName.cpp
	shared/VerifyAndLockName.h

	shared/centralConnectionServer/CentralConnectionServerMessages.cpp
	shared/centralConnectionServer/CentralConnectionServerMessages.h
	shared/centralConnectionServer/SetConnectionServerPublic.cpp
	shared/centralConnectionServer/SetConnectionServerPublic.h
	shared/centralConnectionServer/UpdateConnectionServerStatus.cpp
	shared/centralConnectionServer/UpdateConnectionServerStatus.h
	shared/centralConnectionServer/UpdatePlayerCountMessage.cpp
	shared/centralConnectionServer/UpdatePlayerCountMessage.h
	shared/centralConnectionServer/ValidateCharacterForLoginMessage.cpp
	shared/centralConnectionServer/ValidateCharacterForLoginMessage.h
	shared/centralConnectionServer/ValidateCharacterForLoginReplyMessage.cpp
	shared/centralConnectionServer/ValidateCharacterForLoginReplyMessage.h

	shared/centralGameServer/AccountFeatureIdRequest.cpp
	shared/centralGameServer/AccountFeatureIdRequest.h
	shared/centralGameServer/AccountFeatureIdResponse.cpp
	shared/centralGameServer/AccountFeatureIdResponse.h
	shared/centralGameServer/AddCharacterMessage.cpp
	shared/centralGameServer/AddCharacterMessage.h
	shared/centralGameServer/AddObjectIdBlockMessage.cpp
	shared/centralGameServer/AddObjectIdBlockMessage.h
	shared/centralGameServer/AdjustAccountFeatureIdRequest.cpp
	shared/centralGameServer/AdjustAccountFeatureIdRequest.h
	shared/centralGameServer/AdjustAccountFeatureIdResponse.cpp
	shared/centralGameServer/AdjustAccountFeatureIdResponse.h
	shared/centralGameServer/CentralGameServerMessages.cpp
	shared/centralGameServer/CentralGameServerMessages.h
	shared/centralGameServer/CentralPingMessage.cpp
	shared/centralGameServer/CentralPingMessage.h
	shared/centralGameServer/ChangeUniverseProcessMessage.cpp
	shared/centralGameServer/ChangeUniverseProcessMessage.h
	shared/centralGameServer/CharacterListMessage.cpp
	shared/centralGameServer/CharacterListMessage.h
	shared/centralGameServer/CharacterTransferStatusMessage.cpp
	shared/centralGameServer/CharacterTransferStatusMessage.h
	shared/centralGameServer/ChunkCompleteMessage.cpp
	shared/centralGameServer/ChunkCompleteMessage.h
	shared/centralGameServer/ChunkObjectListMessage.cpp
	shared/centralGameServer/ChunkObjectListMessage.h
	shared/centralGameServer/ClaimRewardsMessage.cpp
	shared/centralGameServer/ClaimRewardsMessage.h
	shared/centralGameServer/ClaimRewardsReplyMessage.cpp
	shared/centralGameServer/ClaimRewardsReplyMessage.h
	shared/centralGameServer/CreateNewObjectMessage.cpp
	shared/centralGameServer/CreateNewObjectMessage.h
	shared/centralGameServer/CSDBNetMessages.cpp
	shared/centralGameServer/CSDBNetMessages.h
	shared/centralGameServer/DownloadCharacterMessage.cpp
	shared/centralGameServer/DownloadCharacterMessage.h
	shared/centralGameServer/ExcommunicateGameServerMessage.cpp
	shared/centralGameServer/ExcommunicateGameServerMessage.h
	shared/centralGameServer/FailedToLoadObjectMessage.cpp
	shared/centralGameServer/FailedToLoadObjectMessage.h
	shared/centralGameServer/FeatureIdTransactionRequest.cpp
	shared/centralGameServer/FeatureIdTransactionRequest.h
	shared/centralGameServer/FeatureIdTransactionResponse.cpp
	shared/centralGameServer/FeatureIdTransactionResponse.h
	shared/centralGameServer/FeatureIdTransactionSyncUpdate.cpp
	shared/centralGameServer/FeatureIdTransactionSyncUpdate.h
	shared/centralGameServer/FlagObjectForDeleteMessage.cpp
	shared/centralGameServer/FlagObjectForDeleteMessage.h
	shared/centralGameServer/ForceUnloadObjectMessage.cpp
	shared/centralGameServer/ForceUnloadObjectMessage.h
	shared/centralGameServer/GameServerCSRequestMessage.cpp
	shared/centralGameServer/GameServerCSRequestMessage.h
	shared/centralGameServer/GameServerCSResponseMessage.cpp
	shared/centralGameServer/GameServerCSResponseMessage.h
	shared/centralGameServer/GameServerReadyMessage.cpp
	shared/centralGameServer/GameServerReadyMessage.h
	shared/centralGameServer/GameServerUniverseLoadedMessage.cpp
	shared/centralGameServer/GameServerUniverseLoadedMessage.h
	shared/centralGameServer/LoadObjectMessage.cpp
	shared/centralGameServer/LoadObjectMessage.h
	shared/centralGameServer/LoadUniverseMessage.cpp
	shared/centralGameServer/LoadUniverseMessage.h
	shared/centralGameServer/MessageToAckMessage.cpp
	shared/centralGameServer/MessageToAckMessage.h
	shared/centralGameServer/MessageToMessage.cpp
	shared/centralGameServer/MessageToMessage.h
	shared/centralGameServer/MessageToPayload.cpp
	shared/centralGameServer/MessageToPayload.h
	shared/centralGameServer/MessageToPayloadImpl.cpp
	shared/centralGameServer/MessageToPayloadImpl.h
	shared/centralGameServer/PlanetObjectIdMessage.cpp
	shared/centralGameServer/PlanetObjectIdMessage.h
	shared/centralGameServer/PopulationListMessage.cpp
	shared/centralGameServer/PopulationListMessage.h
	shared/centralGameServer/PreloadFinishedMessage.cpp
	shared/centralGameServer/PreloadFinishedMessage.h
	shared/centralGameServer/PreloadRequestCompleteMessage.cpp
	shared/centralGameServer/PreloadRequestCompleteMessage.h
	shared/centralGameServer/ReleaseAuthoritativeMessage.cpp
	shared/centralGameServer/ReleaseAuthoritativeMessage.h
	shared/centralGameServer/RequestChunkMessage.cpp
	shared/centralGameServer/RequestChunkMessage.h
	shared/centralGameServer/RequestObjectIdsMessage.cpp
	shared/centralGameServer/RequestObjectIdsMessage.h
	shared/centralGameServer/RequestObjectMessage.cpp
	shared/centralGameServer/RequestObjectMessage.h
	shared/centralGameServer/RequestPlanetObjectIdMessage.cpp
	shared/centralGameServer/RequestPlanetObjectIdMessage.h
	shared/centralGameServer/RequestUnloadObjectMessage.cpp
	shared/centralGameServer/RequestUnloadObjectMessage.h
	shared/centralGameServer/SceneTransferMessages.cpp
	shared/centralGameServer/SceneTransferMessages.h
	shared/centralGameServer/SetAuthoritativeMessage.cpp
	shared/centralGameServer/SetAuthoritativeMessage.h
	shared/centralGameServer/SetObjectPositionMessage.cpp
	shared/centralGameServer/SetObjectPositionMessage.h
	shared/centralGameServer/SetPlanetServerMessage.cpp
	shared/centralGameServer/SetPlanetServerMessage.h
	shared/centralGameServer/SetUniverseAuthoritativeMessage.cpp
	shared/centralGameServer/SetUniverseAuthoritativeMessage.h
	shared/centralGameServer/StructureListMessage.cpp
	shared/centralGameServer/StructureListMessage.h
	shared/centralGameServer/ToggleAvatarLoginStatus.cpp
	shared/centralGameServer/ToggleAvatarLoginStatus.h
	shared/centralGameServer/UploadCharacterMessage.cpp
	shared/centralGameServer/UploadCharacterMessage.h
	shared/centralGameServer/UnloadObjectMessage.cpp
	shared/centralGameServer/UnloadObjectMessage.h

	shared/centralPlanetServer/CentralPlanetServerConnect.cpp
	shared/centralPlanetServer/CentralPlanetServerConnect.h
	shared/centralPlanetServer/GameServerForLoginMessage.cpp
	shared/centralPlanetServer/GameServerForLoginMessage.h
	shared/centralPlanetServer/RequestGameServerForLoginMessage.cpp
	shared/centralPlanetServer/RequestGameServerForLoginMessage.h

	shared/centralTaskManager/CentralTaskMessages.cpp
	shared/centralTaskManager/CentralTaskMessages.h
	shared/centralTaskManager/TaskProcessDiedMessage.cpp
	shared/centralTaskManager/TaskProcessDiedMessage.h

	shared/commoditiesSwgDatabase/CommoditiesLoadDoneMessage.cpp
	shared/commoditiesSwgDatabase/CommoditiesLoadDoneMessage.h
	shared/commoditiesSwgDatabase/CMCreateAuctionMessage.cpp
	shared/commoditiesSwgDatabase/CMCreateAuctionMessage.h
	shared/commoditiesSwgDatabase/CMUpdateAuctionMessage.cpp
	shared/commoditiesSwgDatabase/CMUpdateAuctionMessage.h
	shared/commoditiesSwgDatabase/CMDeleteAuctionMessage.cpp
	shared/commoditiesSwgDatabase/CMDeleteAuctionMessage.h
	shared/commoditiesSwgDatabase/CMCreateAuctionBidMessage.cpp
	shared/commoditiesSwgDatabase/CMCreateAuctionBidMessage.h
	shared/commoditiesSwgDatabase/CMCreateLocationMessage.cpp
	shared/commoditiesSwgDatabase/CMCreateLocationMessage.h
	shared/commoditiesSwgDatabase/CMUpdateLocationMessage.cpp
	shared/commoditiesSwgDatabase/CMUpdateLocationMessage.h
	shared/commoditiesSwgDatabase/CMDeleteLocationMessage.cpp
	shared/commoditiesSwgDatabase/CMDeleteLocationMessage.h
	shared/commoditiesSwgDatabase/GetAuctionLocationsMessage.cpp
	shared/commoditiesSwgDatabase/GetAuctionLocationsMessage.h
	shared/commoditiesSwgDatabase/GetMarketAuctionAttributesMessage.cpp
	shared/commoditiesSwgDatabase/GetMarketAuctionAttributesMessage.h
	shared/commoditiesSwgDatabase/GetMarketAuctionBidsMessage.cpp
	shared/commoditiesSwgDatabase/GetMarketAuctionBidsMessage.h
	shared/commoditiesSwgDatabase/GetMarketAuctionsMessage.cpp
	shared/commoditiesSwgDatabase/GetMarketAuctionsMessage.h
	shared/commoditiesSwgDatabase/LoadCommoditiesMessage.cpp
	shared/commoditiesSwgDatabase/LoadCommoditiesMessage.h

	shared/core/FirstServerNetworkMessages.h
	shared/core/SetupServerNetworkMessages.cpp
	shared/core/SetupServerNetworkMessages.h
	shared/core/TaskConsoleCommand.cpp
	shared/core/TaskConsoleCommand.h

	shared/gameCommoditiesServer/AcceptHighBidMessage.cpp
	shared/gameCommoditiesServer/AcceptHighBidMessage.h
	shared/gameCommoditiesServer/AddAuctionMessage.cpp
	shared/gameCommoditiesServer/AddAuctionMessage.h
	shared/gameCommoditiesServer/AddBidMessage.cpp
	shared/gameCommoditiesServer/AddBidMessage.h
	shared/gameCommoditiesServer/AddImmediateAuctionMessage.cpp
	shared/gameCommoditiesServer/AddImmediateAuctionMessage.h
	shared/gameCommoditiesServer/AuctionBase.h
	shared/gameCommoditiesServer/AuctionData.cpp
	shared/gameCommoditiesServer/AuctionData.h
	shared/gameCommoditiesServer/CancelAuctionMessage.cpp
	shared/gameCommoditiesServer/CancelAuctionMessage.h
	shared/gameCommoditiesServer/CleanupInvalidItemRetrievalMessage.cpp
	shared/gameCommoditiesServer/CleanupInvalidItemRetrievalMessage.h
	shared/gameCommoditiesServer/CreateVendorMarketMessage.cpp
	shared/gameCommoditiesServer/CreateVendorMarketMessage.h
	shared/gameCommoditiesServer/DeleteAuctionLocationMessage.cpp
	shared/gameCommoditiesServer/DeleteAuctionLocationMessage.h
	shared/gameCommoditiesServer/DestroyVendorMarketMessage.cpp
	shared/gameCommoditiesServer/DestroyVendorMarketMessage.h
	shared/gameCommoditiesServer/GetItemDetailsMessage.cpp
	shared/gameCommoditiesServer/GetItemDetailsMessage.h
	shared/gameCommoditiesServer/GetItemMessage.cpp
	shared/gameCommoditiesServer/GetItemMessage.h
	shared/gameCommoditiesServer/GetPlayerVendorCountMessage.cpp
	shared/gameCommoditiesServer/GetPlayerVendorCountMessage.h
	shared/gameCommoditiesServer/GetVendorOwnerMessage.cpp
	shared/gameCommoditiesServer/GetVendorOwnerMessage.h
	shared/gameCommoditiesServer/GetVendorValueMessage.cpp
	shared/gameCommoditiesServer/GetVendorValueMessage.h
	shared/gameCommoditiesServer/ItemMovedMessage.cpp
	shared/gameCommoditiesServer/ItemMovedMessage.h
	shared/gameCommoditiesServer/OnAcceptHighBidMessage.cpp
	shared/gameCommoditiesServer/OnAcceptHighBidMessage.h
	shared/gameCommoditiesServer/OnAddAuctionMessage.cpp
	shared/gameCommoditiesServer/OnAddAuctionMessage.h
	shared/gameCommoditiesServer/OnAddBidMessage.cpp
	shared/gameCommoditiesServer/OnAddBidMessage.h
	shared/gameCommoditiesServer/OnAuctionExpiredMessage.cpp
	shared/gameCommoditiesServer/OnAuctionExpiredMessage.h
	shared/gameCommoditiesServer/OnCancelAuctionMessage.cpp
	shared/gameCommoditiesServer/OnCancelAuctionMessage.h
	shared/gameCommoditiesServer/OnCleanupInvalidItemRetrievalMessage.cpp
	shared/gameCommoditiesServer/OnCleanupInvalidItemRetrievalMessage.h
	shared/gameCommoditiesServer/OnCreateVendorMarketMessage.cpp
	shared/gameCommoditiesServer/OnCreateVendorMarketMessage.h
	shared/gameCommoditiesServer/OnGetItemDetailsMessage.cpp
	shared/gameCommoditiesServer/OnGetItemDetailsMessage.h
	shared/gameCommoditiesServer/OnGetItemMessage.cpp
	shared/gameCommoditiesServer/OnGetItemMessage.h
	shared/gameCommoditiesServer/OnGetPlayerVendorCountMessage.cpp
	shared/gameCommoditiesServer/OnGetPlayerVendorCountMessage.h
	shared/gameCommoditiesServer/OnGetVendorOwnerMessage.cpp
	shared/gameCommoditiesServer/OnGetVendorOwnerMessage.h
	shared/gameCommoditiesServer/OnGetVendorValueMessage.cpp
	shared/gameCommoditiesServer/OnGetVendorValueMessage.h
	shared/gameCommoditiesServer/OnItemExpiredMessage.cpp
	shared/gameCommoditiesServer/OnItemExpiredMessage.h
	shared/gameCommoditiesServer/OnPermanentAuctionPurchasedMessage.cpp
	shared/gameCommoditiesServer/OnPermanentAuctionPurchasedMessage.h
	shared/gameCommoditiesServer/OnQueryAuctionHeadersMessage.cpp
	shared/gameCommoditiesServer/OnQueryAuctionHeadersMessage.h
	shared/gameCommoditiesServer/OnQueryVendorItemCountReplyMessage.cpp
	shared/gameCommoditiesServer/OnQueryVendorItemCountReplyMessage.h
	shared/gameCommoditiesServer/OnUpdateVendorSearchOptionMessage.cpp
	shared/gameCommoditiesServer/OnUpdateVendorSearchOptionMessage.h
	shared/gameCommoditiesServer/OnVendorRefuseItemMessage.cpp
	shared/gameCommoditiesServer/OnVendorRefuseItemMessage.h
	shared/gameCommoditiesServer/QueryAuctionHeadersMessage.cpp
	shared/gameCommoditiesServer/QueryAuctionHeadersMessage.h
	shared/gameCommoditiesServer/QueryVendorItemCountMessage.cpp
	shared/gameCommoditiesServer/QueryVendorItemCountMessage.h
	shared/gameCommoditiesServer/SetEntranceChargeMessage.cpp
	shared/gameCommoditiesServer/SetEntranceChargeMessage.h
	shared/gameCommoditiesServer/SetGameTimeMessage.cpp
	shared/gameCommoditiesServer/SetGameTimeMessage.h
	shared/gameCommoditiesServer/SetSalesTaxMessage.cpp
	shared/gameCommoditiesServer/SetSalesTaxMessage.h
	shared/gameCommoditiesServer/UpdateVendorSearchOptionMessage.cpp
	shared/gameCommoditiesServer/UpdateVendorSearchOptionMessage.h
	shared/gameCommoditiesServer/UpdateVendorStatusMessage.cpp
	shared/gameCommoditiesServer/UpdateVendorStatusMessage.h
	shared/gameCommoditiesServer/VendorStatusChangeMessage.cpp
	shared/gameCommoditiesServer/VendorStatusChangeMessage.h

	shared/gameConnectionServer/GameConnectionServerMessages.cpp
	shared/gameConnectionServer/GameConnectionServerMessages.h
	shared/gameConnectionServer/NewClient.cpp
	shared/gameConnectionServer/NewClient.h

	shared/gameGameServer/AddResourceTypeMessage.cpp
	shared/gameGameServer/AddResourceTypeMessage.h
	shared/gameGameServer/AiCreatureStateMessage.cpp
	shared/gameGameServer/AiCreatureStateMessage.h
	shared/gameGameServer/AiMovementMessage.cpp
	shared/gameGameServer/AiMovementMessage.h
	shared/gameGameServer/AuthTransferClientMessage.cpp
	shared/gameGameServer/AuthTransferClientMessage.h
	shared/gameGameServer/BiographyMessage.cpp
	shared/gameGameServer/BiographyMessage.h
	shared/gameGameServer/BountyHunterTargetListMessage.cpp
	shared/gameGameServer/BountyHunterTargetListMessage.h
	shared/gameGameServer/BountyHunterTargetMessage.cpp
	shared/gameGameServer/BountyHunterTargetMessage.h
	shared/gameGameServer/CharacterNamesMessage.cpp
	shared/gameGameServer/CharacterNamesMessage.h
	shared/gameGameServer/CreateDynamicSpawnRegionCircleMessage.cpp
	shared/gameGameServer/CreateDynamicSpawnRegionCircleMessage.h
	shared/gameGameServer/CreateDynamicRegionCircleMessage.cpp
	shared/gameGameServer/CreateDynamicRegionCircleMessage.h
	shared/gameGameServer/CreateDynamicRegionRectangleMessage.cpp
	shared/gameGameServer/CreateDynamicRegionRectangleMessage.h
	shared/gameGameServer/CreateGroupMessage.cpp
	shared/gameGameServer/CreateGroupMessage.h
	shared/gameGameServer/CreateObjectMessage.cpp
	shared/gameGameServer/CreateObjectMessage.h
	shared/gameGameServer/CreateSyncUiMessage.cpp
	shared/gameGameServer/CreateSyncUiMessage.h
	shared/gameGameServer/EnableNewJediTrackingMessage.cpp
	shared/gameGameServer/EnableNewJediTrackingMessage.h
	shared/gameGameServer/EndBaselinesMessage.cpp
	shared/gameGameServer/EndBaselinesMessage.h
	shared/gameGameServer/ExchangeListCreditsMessage.cpp
	shared/gameGameServer/ExchangeListCreditsMessage.h
	shared/gameGameServer/GameGameServerMessages.cpp
	shared/gameGameServer/GameGameServerMessages.h
	shared/gameGameServer/GameServerConnectAck.cpp
	shared/gameGameServer/GameServerConnectAck.h
	shared/gameGameServer/GameServerMessageInterface.cpp
	shared/gameGameServer/GameServerMessageInterface.h
	shared/gameGameServer/GetMoneyFromOfflineObjectMessage.cpp
	shared/gameGameServer/GetMoneyFromOfflineObjectMessage.h
	shared/gameGameServer/GroupMemberParam.cpp
	shared/gameGameServer/GroupMemberParam.h
	shared/gameGameServer/GroupMemberParamArchive.cpp
	shared/gameGameServer/GroupMemberParamArchive.h
	shared/gameGameServer/LoadContainedObjectMessage.cpp
	shared/gameGameServer/LoadContainedObjectMessage.h
	shared/gameGameServer/LoadContentsMessage.cpp
	shared/gameGameServer/LoadContentsMessage.h
	shared/gameGameServer/LoadStructureMessage.cpp
	shared/gameGameServer/LoadStructureMessage.h
	shared/gameGameServer/LocateObjectResponseMessage.cpp
	shared/gameGameServer/LocateObjectResponseMessage.h
	shared/gameGameServer/LocatePlayerResponseMessage.cpp
	shared/gameGameServer/LocatePlayerResponseMessage.h
	shared/gameGameServer/LocateStructureMessage.cpp
	shared/gameGameServer/LocateStructureMessage.h
	shared/gameGameServer/MessageQueueAlterAttribute.cpp
	shared/gameGameServer/MessageQueueAlterAttribute.h
	shared/gameGameServer/MessageQueueCommandQueueEnqueueFwd.cpp
	shared/gameGameServer/MessageQueueCommandQueueEnqueueFwd.h
	shared/gameGameServer/MessageQueueCommandQueueForceExecuteCommandFwd.cpp
	shared/gameGameServer/MessageQueueCommandQueueForceExecuteCommandFwd.h
	shared/gameGameServer/MessageQueueGrantOfflineXp.cpp
	shared/gameGameServer/MessageQueueGrantOfflineXp.h
	shared/gameGameServer/MessageQueuePvpCommand.cpp
	shared/gameGameServer/MessageQueuePvpCommand.h
	shared/gameGameServer/MessageQueueScriptTrigger.cpp
	shared/gameGameServer/MessageQueueScriptTrigger.h
	shared/gameGameServer/MessageQueueSetState.cpp
	shared/gameGameServer/MessageQueueSetState.h
	shared/gameGameServer/MessageQueueTeleportObject.cpp
	shared/gameGameServer/MessageQueueTeleportObject.h
	shared/gameGameServer/PersistedPlayerMessage.cpp
	shared/gameGameServer/PersistedPlayerMessage.h
	shared/gameGameServer/PlayedTimeAccumMessage.cpp
	shared/gameGameServer/PlayedTimeAccumMessage.h
	shared/gameGameServer/ProfilerOperationMessage.cpp
	shared/gameGameServer/ProfilerOperationMessage.h
	shared/gameGameServer/ReloadAdminTableMessage.cpp
	shared/gameGameServer/ReloadAdminTableMessage.h
	shared/gameGameServer/ReloadCommandTableMessage.cpp
	shared/gameGameServer/ReloadCommandTableMessage.h
	shared/gameGameServer/ReloadDatatableMessage.cpp
	shared/gameGameServer/ReloadDatatableMessage.h
	shared/gameGameServer/ReloadScriptMessage.cpp
	shared/gameGameServer/ReloadScriptMessage.h
	shared/gameGameServer/ReloadTemplateMessage.cpp
	shared/gameGameServer/ReloadTemplateMessage.h
	shared/gameGameServer/RenameCharacterMessage.cpp
	shared/gameGameServer/RenameCharacterMessage.h
	shared/gameGameServer/RequestBiographyMessage.cpp
	shared/gameGameServer/RequestBiographyMessage.h
	shared/gameGameServer/RestartServerMessage.cpp
	shared/gameGameServer/RestartServerMessage.h
	shared/gameGameServer/RetrievedItemLoadMessage.cpp
	shared/gameGameServer/RetrievedItemLoadMessage.h
	shared/gameGameServer/StructuresForPurgeMessage.cpp
	shared/gameGameServer/StructuresForPurgeMessage.h
	shared/gameGameServer/SynchronizeScriptVarDeltasMessage.cpp
	shared/gameGameServer/SynchronizeScriptVarDeltasMessage.h
	shared/gameGameServer/SynchronizeScriptVarsMessage.cpp
	shared/gameGameServer/SynchronizeScriptVarsMessage.h
	shared/gameGameServer/TeleportMessage.cpp
	shared/gameGameServer/TeleportMessage.h
	shared/gameGameServer/TeleportToMessage.cpp
	shared/gameGameServer/TeleportToMessage.h
	shared/gameGameServer/UnloadedPlayerMessage.cpp
	shared/gameGameServer/UnloadedPlayerMessage.h
	shared/gameGameServer/UpdateObjectPositionMessage.cpp
	shared/gameGameServer/UpdateObjectPositionMessage.h

	shared/gamePlanetServer/FactionalSystemMessage.cpp
	shared/gamePlanetServer/FactionalSystemMessage.h
	shared/gamePlanetServer/FirstPlanetGameServerIdMessage.cpp
	shared/gamePlanetServer/FirstPlanetGameServerIdMessage.h
	shared/gamePlanetServer/GameServerForceChangeAuthorityMessage.cpp
	shared/gamePlanetServer/GameServerForceChangeAuthorityMessage.h
	shared/gamePlanetServer/LocationRequest.cpp
	shared/gamePlanetServer/LocationRequest.h
	shared/gamePlanetServer/LocationResponse.cpp
	shared/gamePlanetServer/LocationResponse.h
	shared/gamePlanetServer/PlanetLoadCharacterMessage.cpp
	shared/gamePlanetServer/PlanetLoadCharacterMessage.h
	shared/gamePlanetServer/PlanetRemoveObject.cpp
	shared/gamePlanetServer/PlanetRemoveObject.h
	shared/gamePlanetServer/UnloadProxyMessage.cpp
	shared/gamePlanetServer/UnloadProxyMessage.h
	shared/gamePlanetServer/UpdateObjectOnPlanetMessage.cpp
	shared/gamePlanetServer/UpdateObjectOnPlanetMessage.h

	shared/gameStationPlayersCollector/SPCharacterProfileMessage.cpp
	shared/gameStationPlayersCollector/SPCharacterProfileMessage.h

	shared/gameTaskManager/GameTaskManagerMessages.cpp
	shared/gameTaskManager/GameTaskManagerMessages.h

	shared/loginCentralServer/ConnectionServerDown.cpp
	shared/loginCentralServer/ConnectionServerDown.h
	shared/loginCentralServer/CSToolRequest.cpp
	shared/loginCentralServer/CSToolRequest.h
	shared/loginCentralServer/CSToolResponse.cpp
	shared/loginCentralServer/CSToolResponse.h
	shared/loginCentralServer/LoginClusterName.cpp
	shared/loginCentralServer/LoginClusterName.h
	shared/loginCentralServer/LoginClusterName2.cpp
	shared/loginCentralServer/LoginClusterName2.h
	shared/loginCentralServer/LoginConnectionServerAddress.cpp
	shared/loginCentralServer/LoginConnectionServerAddress.h
	shared/loginCentralServer/LoginCreateCharacterAckMessage.cpp
	shared/loginCentralServer/LoginCreateCharacterAckMessage.h
	shared/loginCentralServer/LoginCreateCharacterMessage.cpp
	shared/loginCentralServer/LoginCreateCharacterMessage.h
	shared/loginCentralServer/LoginKeyPush.cpp
	shared/loginCentralServer/LoginKeyPush.h
	shared/loginCentralServer/LoginRestoreCharacterMessage.cpp
	shared/loginCentralServer/LoginRestoreCharacterMessage.h
	shared/loginCentralServer/LoginUpgradeAccountMessage.cpp
	shared/loginCentralServer/LoginUpgradeAccountMessage.h
	shared/loginCentralServer/ServerDeleteCharacterMessage.cpp
	shared/loginCentralServer/ServerDeleteCharacterMessage.h
	shared/loginCentralServer/UpdateLoginConnectionServerStatus.cpp
	shared/loginCentralServer/UpdateLoginConnectionServerStatus.h
	shared/loginCentralServer/ValidateAccountMessage.cpp
	shared/loginCentralServer/ValidateAccountMessage.h
	shared/loginCentralServer/ValidateAccountReplyMessage.cpp
	shared/loginCentralServer/ValidateAccountReplyMessage.h

	shared/metricsMessages/MetricsDataMessage.cpp
	shared/metricsMessages/MetricsDataMessage.h
	shared/metricsMessages/MetricsInitiationMessage.cpp
	shared/metricsMessages/MetricsInitiationMessage.h

	shared/transferServer/TransferReplyCharacterList.cpp
	shared/transferServer/TransferReplyCharacterList.h
	shared/transferServer/TransferRequestMoveValidation.cpp
	shared/transferServer/TransferRequestMoveValidation.h
	shared/transferServer/TransferCharacterData.cpp
	shared/transferServer/TransferCharacterDataArchive.cpp
	shared/transferServer/TransferReplyMoveValidation.cpp
	shared/transferServer/TransferReplyMoveValidation.h
	shared/transferServer/TransferAccountData.cpp
	shared/transferServer/TransferAccountDataArchive.cpp
)

if(WIN32)
	set(PLATFORM_SOURCES
		win32/FirstServerNetworkMessages.cpp
	)
else()
	set(PLATFORM_SOURCES "")
endif()

include_directories(
	${CMAKE_CURRENT_SOURCE_DIR}/shared
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedDebug/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedFile/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedFoundation/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedFoundationTypes/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedGame/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedMath/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedMathArchive/include/public
	
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedMessageDispatch/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedNetwork/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedNetworkMessages/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedObject/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedRandom/include/public
	${SWG_ENGINE_SOURCE_DIR}/shared/library/sharedUtility/include/public
	${SWG_ENGINE_SOURCE_DIR}/server/library/serverGame/include/public
	${SWG_ENGINE_SOURCE_DIR}/server/library/serverKeyShare/include/public
	${SWG_ENGINE_SOURCE_DIR}/server/library/serverUtility/include/public
	${SWG_GAME_SOURCE_DIR}/shared/library/swgSharedUtility/include/public
	${SWG_EXTERNALS_SOURCE_DIR}/ours/library/archive/include
	${SWG_EXTERNALS_SOURCE_DIR}/ours/library/localization/include
	${SWG_EXTERNALS_SOURCE_DIR}/ours/library/localizationArchive/include/public
	${SWG_EXTERNALS_SOURCE_DIR}/ours/library/singleton/include
	${SWG_EXTERNALS_SOURCE_DIR}/ours/library/unicode/include
	${SWG_EXTERNALS_SOURCE_DIR}/ours/library/unicodeArchive/include/public
)

add_library(serverNetworkMessages STATIC
	${SHARED_SOURCES}
	${PLATFORM_SOURCES}
)

target_link_libraries(serverNetworkMessages
	sharedFoundation
	archive
	localization
	localizationArchive
	unicode
	unicodeArchive
)
