# Function: <code>tboot_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e250)
Location: arch/x86/kernel/tboot.c:277
Inline: False
```
**Symbols:**

```
ffffffff8103e250-ffffffff8103e38e: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e070)
Location: arch/x86/kernel/tboot.c:271
Inline: False
```
**Symbols:**

```
ffffffff8103e070-ffffffff8103e1ae: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103d920)
Location: arch/x86/kernel/tboot.c:271
Inline: False
```
**Symbols:**

```
ffffffff8103d920-ffffffff8103da5e: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103b990)
Location: arch/x86/kernel/tboot.c:275
Inline: True
```
**Symbols:**

```
ffffffff8103b990-ffffffff8103baec: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e3b0)
Location: arch/x86/kernel/tboot.c:286
Inline: True
```
**Symbols:**

```
ffffffff8103e3b0-ffffffff8103e50c: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:286
Inline: True
```
**Symbols:**

```
ffffffff8103f940-ffffffff8103fa91: tboot_sleep (STB_LOCAL)
ffffffff8103fba5-ffffffff8103fbbb: tboot_sleep.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81040f68)
Location: arch/x86/kernel/tboot.c:286
Inline: True
```
**Symbols:**

```
ffffffff81040f40-ffffffff81041091: tboot_sleep (STB_LOCAL)
ffffffff810411a5-ffffffff810411bb: tboot_sleep.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043659)
Location: arch/x86/kernel/tboot.c:273
Inline: True
```
**Symbols:**

```
ffffffff81043630-ffffffff81043764: tboot_sleep (STB_LOCAL)
ffffffff8104388d-ffffffff810438a5: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043da9)
Location: arch/x86/kernel/tboot.c:273
Inline: True
```
**Symbols:**

```
ffffffff81043d80-ffffffff81043eb4: tboot_sleep (STB_LOCAL)
ffffffff81043fdd-ffffffff81043ff5: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104775a)
Location: arch/x86/kernel/tboot.c:275
Inline: True
```
**Symbols:**

```
ffffffff81047730-ffffffff810477c0: tboot_sleep (STB_LOCAL)
ffffffff81047c34-ffffffff81047c4b: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81046f8a)
Location: arch/x86/kernel/tboot.c:276
Inline: True
```
**Symbols:**

```
ffffffff81046f60-ffffffff81046ff0: tboot_sleep (STB_LOCAL)
ffffffff81bd4eab-ffffffff81bd4ec2: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810488ff)
Location: arch/x86/kernel/tboot.c:284
Inline: True
```
**Symbols:**

```
ffffffff810488d0-ffffffff81048a0b: tboot_sleep (STB_LOCAL)
ffffffff81bc725e-ffffffff81bc7276: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104f291)
Location: arch/x86/kernel/tboot.c:284
Inline: True
```
**Symbols:**

```
ffffffff8104f260-ffffffff8104f3db: tboot_sleep (STB_LOCAL)
ffffffff81c9a856-ffffffff81c9a86e: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:283
Inline: False
```
**Symbols:**

```
ffffffff8105a4f0-ffffffff8105a677: tboot_sleep (STB_LOCAL)
ffffffff81e49cd8-ffffffff81e49cee: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810682b0)
Location: arch/x86/kernel/tboot.c:282
Inline: False
```
**Symbols:**

```
ffffffff810682b0-ffffffff81068444: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81069bd0)
Location: arch/x86/kernel/tboot.c:282
Inline: False
```
**Symbols:**

```
ffffffff81069bd0-ffffffff81069d64: tboot_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810710a0)
Location: arch/x86/kernel/tboot.c:282
Inline: False
```
**Symbols:**

```
ffffffff810710a0-ffffffff81071234: tboot_sleep (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043f29)
Location: arch/x86/kernel/tboot.c:273
Inline: True
```
**Symbols:**

```
ffffffff81043f00-ffffffff81044034: tboot_sleep (STB_LOCAL)
ffffffff8104415d-ffffffff81044175: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81033549)
Location: arch/x86/kernel/tboot.c:273
Inline: True
```
**Symbols:**

```
ffffffff81033520-ffffffff81033654: tboot_sleep (STB_LOCAL)
ffffffff8103377d-ffffffff81033795: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81043d69)
Location: arch/x86/kernel/tboot.c:273
Inline: True
```
**Symbols:**

```
ffffffff81043d40-ffffffff81043e74: tboot_sleep (STB_LOCAL)
ffffffff81043f9d-ffffffff81043fb5: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81045169)
Location: arch/x86/kernel/tboot.c:273
Inline: True
```
**Symbols:**

```
ffffffff81045140-ffffffff81045274: tboot_sleep (STB_LOCAL)
ffffffff8104539d-ffffffff810453b5: tboot_sleep.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
