# Function: <code>suspend_devices_and_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810ce2b0)
Location: kernel/power/suspend.c:403
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:power_down
```
**Symbols:**

```
ffffffff810ce2b0-ffffffff810ce9dd: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d2e10)
Location: kernel/power/suspend.c:405
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:power_down
```
**Symbols:**

```
ffffffff810d2e10-ffffffff810d34f0: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d99a0)
Location: kernel/power/suspend.c:428
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:power_down
```
**Symbols:**

```
ffffffff810d99a0-ffffffff810da07c: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d8980)
Location: kernel/power/suspend.c:451
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810d8980-ffffffff810d9155: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e0a70)
Location: kernel/power/suspend.c:471
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810e0a70-ffffffff810e12b7: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810e98a5-ffffffff810e9959: suspend_devices_and_enter.cold.5 (STB_LOCAL)
ffffffff810e9010-ffffffff810e9802: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:482
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810f4ec5-ffffffff810f4f79: suspend_devices_and_enter.cold.6 (STB_LOCAL)
ffffffff810f4630-ffffffff810f4e22: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:486
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810fd454-ffffffff810fd495: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff810fd0f0-ffffffff810fd34c: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff811098a0-ffffffff811098e1: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81109510-ffffffff8110976c: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:power_down
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff811145a9-ffffffff811145ea: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81114140-ffffffff8111439c: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:power_down
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81bdee3a-ffffffff81bdee7b: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81110db0-ffffffff81110fdc: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81bd0edc-ffffffff81bd0f1d: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81111810-ffffffff81111a3c: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:474
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81ca9c66-ffffffff81ca9cbe: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81131280-ffffffff811314be: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:475
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff81e59bfc-ffffffff81e59c54: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81152c40-ffffffff81152eea: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:482
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8205840e-ffffffff82058423: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81181fd0-ffffffff811822b3: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:482
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff820d6cf6-ffffffff820d6d0b: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff81192eb0-ffffffff81193193: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:482
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff821b1f8c-ffffffff821b1fa1: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff811a18a0-ffffffff811a1b83: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffff800010170d38)
Location: kernel/power/suspend.c:476
Inline: False
```
**Symbols:**

```
ffff800010170d38-ffff800010171008: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (c03bb180)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
c03bb180-c03bbb20: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (c0000000001c8840)
Location: kernel/power/suspend.c:476
Inline: False
```
**Symbols:**

```
c0000000001c8840-c0000000001c9484: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (0)
Location: kernel/power/power.h:196
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810f2ce8-ffffffff810f2dce: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff810f2470-ffffffff810f2c4b: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff810ffd70-ffffffff810ffdb1: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff810ff9e0-ffffffff810ffc3c: suspend_devices_and_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int suspend_devices_and_enter(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:476
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
ffffffff8110b110-ffffffff8110b151: suspend_devices_and_enter.cold (STB_LOCAL)
ffffffff8110ad50-ffffffff8110afde: suspend_devices_and_enter (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
