# Function: <code>hpet_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81519e70)
Location: drivers/char/hpet.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff81519e70-ffffffff8151a27e: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8156cb70)
Location: drivers/char/hpet.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff8156cb70-ffffffff8156cf6e: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff815992e0)
Location: drivers/char/hpet.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff815992e0-ffffffff815996de: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff815ad2e0)
Location: drivers/char/hpet.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff815ad2e0-ffffffff815ad6f3: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81613cb0)
Location: drivers/char/hpet.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff81613cb0-ffffffff816140c3: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff8164dc69-ffffffff8164ded9: hpet_alloc.cold.10 (STB_LOCAL)
ffffffff8164da70-ffffffff8164db83: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:839
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff8166bde9-ffffffff8166c059: hpet_alloc.cold.11 (STB_LOCAL)
ffffffff8166bbf0-ffffffff8166bd03: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff816a198d-ffffffff816a1c1c: hpet_alloc.cold (STB_LOCAL)
ffffffff816a1780-ffffffff816a18a5: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff816c46ed-ffffffff816c497c: hpet_alloc.cold (STB_LOCAL)
ffffffff816c4520-ffffffff816c460f: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff81778d75-ffffffff81779004: hpet_alloc.cold (STB_LOCAL)
ffffffff81778bd0-ffffffff81778cbc: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff81c0896a-ffffffff81c08bf9: hpet_alloc.cold (STB_LOCAL)
ffffffff817936a0-ffffffff8179378c: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff81bfa50c-ffffffff81bfa7ae: hpet_alloc.cold (STB_LOCAL)
ffffffff817763a0-ffffffff8177648c: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff81cfaf83-ffffffff81cfb23d: hpet_alloc.cold (STB_LOCAL)
ffffffff817fc130-ffffffff817fc21c: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:800
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff81ec37d7-ffffffff81ec39e3: hpet_alloc.cold (STB_LOCAL)
ffffffff8193ac90-ffffffff8193ad90: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:800
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff82096787-ffffffff820967af: hpet_alloc.cold (STB_LOCAL)
ffffffff81a9b0e0-ffffffff81a9b419: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:800
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff821176cf-ffffffff821176f6: hpet_alloc.cold (STB_LOCAL)
ffffffff81ae6970-ffffffff81ae6cd9: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
  - drivers/char/hpet.c:hpet_acpi_add
```
**Symbols:**

```
ffffffff821f5444-ffffffff821f546b: hpet_alloc.cold (STB_LOCAL)
ffffffff81b39d00-ffffffff81b3a069: hpet_alloc (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff8168a13d-ffffffff8168a3cc: hpet_alloc.cold (STB_LOCAL)
ffffffff81689f70-ffffffff8168a05f: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff81667b5d-ffffffff81667dd3: hpet_alloc.cold (STB_LOCAL)
ffffffff81667990-ffffffff81667a7f: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff816b83ad-ffffffff816b863c: hpet_alloc.cold (STB_LOCAL)
ffffffff816b81e0-ffffffff816b82cf: hpet_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hpet_alloc(struct hpet_data *hdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_reserve_platform_timers
```
**Symbols:**

```
ffffffff816d297d-ffffffff816d2c0c: hpet_alloc.cold (STB_LOCAL)
ffffffff816d27b0-ffffffff816d289f: hpet_alloc (STB_GLOBAL)
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
