# Level
* ` Level.setTile(int, int, int, int, int); `

# ModLIB
* ` ModLIB.clientMessage(str); `
* ` ModLIB.getFileContent(str); `
* ` ModLIB.getTouchX(); `
* ` ModLIB.getTouchY(); `
* ` ModLIB.openOptionsScreen(int); `
* ` ModLIB.openScreen(int ScreenType); `
* ` ModLIB.selectSlot(int); `
* ` ModLIB.setFile(str,str); `
* ` ModLIB.showPopupNotice(str, str); `
* ` ModLIB.showTipMessage(str); `

# Player
* ` Player.buildOrInteract(); `
* ` Player.destroyOrAttack(); `
* ` Player.jump(); `
* ` Player.x(); `
* ` Player.y(); `
* ` Player.z(); `

# Default
* ` getCarriedItem(); `
* ` include(str); `
* ` preventDefault(); `

# Hooks
* ` function attackHook(a, v) {}; `
* ` function destroyBlock(x, y, z, id) {}; `
* ` function leaveGame() {}; `
* ` function modTick() {}; `
* ` function onJump() {}; `
* ` function onMove(x, y, z) {}; `
* ` function onPressBack() {}; `
* ` function screenChangeHook(screenType) {}; `
* ` function useItem(x, y, z, id) {}; `

# ScreenType
* ` ScreenType.CHAT `
* ` ScreenType.INVENTORY `
* ` ScreenType.MOB_EFFECTS `
* ` ScreenType.OPTIONS `
* ` ScreenType.PAUSE `
* ` ScreenType.START `
