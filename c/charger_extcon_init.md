# Function: <code>charger_extcon_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff8168216f)
Location: drivers/power/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e336f)
Location: drivers/power/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817137df)
Location: drivers/power/supply/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172bd57)
Location: drivers/power/supply/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179d4fa)
Location: drivers/power/supply/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e4d32)
Location: drivers/power/supply/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81810437)
Location: drivers/power/supply/charger-manager.c:1198
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff818524c4)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81883eb1)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8195260f)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int charger_extcon_init(struct charger_manager *cm, struct charger_cable *cable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:973
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81955fd0-ffffffff819560f5: charger_extcon_init (STB_LOCAL)
ffffffff81c25585-ffffffff81c255bc: charger_extcon_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8193a2db)
Location: drivers/power/supply/charger-manager.c:973
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff819dea5b)
Location: drivers/power/supply/charger-manager.c:973
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81b434e0)
Location: drivers/power/supply/charger-manager.c:973
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81cd9fb3)
Location: drivers/power/supply/charger-manager.c:973
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81d421ec)
Location: drivers/power/supply/charger-manager.c:973
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81df8b9c)
Location: drivers/power/supply/charger-manager.c:973
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010ad0b90)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0bb13c8)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb4c04)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cd31a)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81879361)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81894d01)
Location: drivers/power/supply/charger-manager.c:1196
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
