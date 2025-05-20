# Function: <code>ntp_update_offset</code>

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
In kernel/time/ntp.c (ffffffff810f77e4)
Location: kernel/time/ntp.c:291
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff810fe916)
Location: kernel/time/ntp.c:294
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff81101706)
Location: kernel/time/ntp.c:294
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff811037f7)
Location: kernel/time/ntp.c:294
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8110e887)
Location: kernel/time/ntp.c:295
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8111a2c7)
Location: kernel/time/ntp.c:295
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff811257c7)
Location: kernel/time/ntp.c:294
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff81130210)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8113c150)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8114a800)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff8114a800-ffffffff8114a985: ntp_update_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81146cf0)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff81146cf0-ffffffff81146e75: ntp_update_offset (STB_LOCAL)
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
In kernel/time/ntp.c (ffffffff81147fb8)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff8116b990-ffffffff8116bb30: ntp_update_offset (STB_LOCAL)
ffffffff81cb1397-ffffffff81cb140f: ntp_update_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff8119f8c0-ffffffff8119fa79: ntp_update_offset (STB_LOCAL)
ffffffff81e62936-ffffffff81e629ae: ntp_update_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff811de600-ffffffff811de7d1: ntp_update_offset (STB_LOCAL)
ffffffff8205b772-ffffffff8205b7ea: ntp_update_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff811f2ad0-ffffffff811f2ca1: ntp_update_offset (STB_LOCAL)
ffffffff820da02c-ffffffff820da0a4: ntp_update_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ntp_update_offset(long int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:296
Inline: False
Direct callers:
  - kernel/time/ntp.c:process_adjtimex_modes
```
**Symbols:**

```
ffffffff81208c10-ffffffff81208de1: ntp_update_offset (STB_LOCAL)
ffffffff821b592b-ffffffff821b59a3: ntp_update_offset.cold (STB_LOCAL)
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
In kernel/time/ntp.c (ffff8000101a6458)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (c03f1684)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (c000000000208750)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffe00013258e)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
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
In kernel/time/ntp.c (ffffffff81134900)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81127360)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81132620)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8113f040)
Location: kernel/time/ntp.c:296
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
