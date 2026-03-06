# movement-system.md

## Purpose

Defines how the player moves through the world, including controls, walking speed, and camera behaviour.

## 目的

プレイヤーが世界を移動する方法（操作・歩行速度・カメラ挙動）を定義する。

---

## Basic Principle

Movement should feel calm and natural, like a slow night walk.  
It should not resemble a fast-paced game. The goal is quiet wandering.

## 基本原則

移動は静かで自然な「夜の散歩」の感覚を目指す。  
ゲームのような速い移動ではなく、穏やかな歩行体験にする。

---

## Player Position

The player remains fixed at the centre of the screen.  
The world scrolls around the player as they move.

## プレイヤー位置

プレイヤーは常に画面中央に固定される。  
移動すると世界の方がスクロールする。

---

## Controls

### PC

- Arrow keys or WASD: move direction  
- Mouse click: walk toward clicked direction

### PC操作

- 矢印キーまたはWASD：移動  
- マウスクリック：クリック方向へ移動

### Mobile

- Tap to walk in that direction  
- Hold to continue moving

### スマートフォン操作

- タップ方向へ歩く  
- 長押しで歩き続ける

---

## Walking Speed

Walking speed should feel relaxed and slightly slow to match the atmosphere of a night walk.  
Final tuning will be performed during beta testing.

## 歩行速度

歩行速度は夜の散歩に合う、少しゆっくりした速度にする。  
最終的な調整はβテストで行う。

---

## Map Boundaries

Maps may have edges. If a player reaches the edge, they stop moving in that direction.

## マップの端

マップには端が存在する場合がある。  
プレイヤーが端に到達した場合、その方向には進めない。

---

## Obstacles

Buildings and certain structures block movement. Players cannot walk through them.

## 障害物

建物や一部の構造物は通行できない障害物として扱う。

---

## Camera Behaviour

The camera follows the player smoothly with no abrupt movement.

## カメラ挙動

カメラはプレイヤーに追従し、急激な動きは行わない。

---

## Future Ideas

- Cat character walking on fences or walls  
- Different movement styles per character type

## 将来のアイデア

- 猫キャラクターが塀や壁の上を歩く  
- キャラクターごとの移動スタイル
