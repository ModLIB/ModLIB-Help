# Level
* ` Level.setTile(int, int, int, int, int); `
* ` Level.getTime(); `
* ` Level.setTime(int); `
* ` Level.getTile(int, int, int); `
* ` Level.playSound(int, int, int, str, int); `
* ` Level.explode(int, int, int, int); `
* ` Level.destroyBlock(int, int, int, bool); `


# ModLIB
* ` ModLIB.clientMessage(str); `
* ` ModLIB.getFileContent(str); `
* ` ModLIB.getTouchX(); `
* ` ModLIB.getTouchY(); `
* ` ModLIB.openOptionsScreen(int); `
* ` ModLIB.openScreen(int ScreenType); `
* ` ModLIB.selectSlot(int); `
* ` ModLIB.setFile(str, str); `
* ` ModLIB.showPopupNotice(str, str); `
* ` ModLIB.showTipMessage(str); `

# Screen
* ` Screen.drawText(int ScreenType, str, int, int); `

# Player
* ` Player.buildOrInteract(); `
* ` Player.destroyOrAttack(); `
* ` Player.jump(); `
* ` Player.setDimension(int); `
* ` Player.x(); `
* ` Player.y(); `
* ` Player.z(); `
* ` Player.isSleeping(); `
* ` Player.isInWater(); `
* ` Player.isInLava(); `
* ` Player.isInvisible(); `

# Item
* ` Item.setGlint(id, bool); `
* ` Item.setIcon(int, str, int); `
* ` Item.setAttackDamage(int, int); `

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
