# Function: <code>default_apic_id_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int default_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054840)
Location: arch/x86/include/asm/apic.h:503
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a270)
Location: arch/x86/include/asm/apic.h:503
Inline: False
```
**Symbols:**

```
ffffffff81054840-ffffffff81054851: default_apic_id_valid (STB_LOCAL)
ffffffff8105a270-ffffffff8105a281: default_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int default_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810549c0)
Location: arch/x86/include/asm/apic.h:510
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4c0)
Location: arch/x86/include/asm/apic.h:510
Inline: False
```
**Symbols:**

```
ffffffff810549c0-ffffffff810549d1: default_apic_id_valid (STB_LOCAL)
ffffffff8105a4c0-ffffffff8105a4d1: default_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int default_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810577a0)
Location: arch/x86/include/asm/apic.h:510
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d2d0)
Location: arch/x86/include/asm/apic.h:510
Inline: False
```
**Symbols:**

```
ffffffff810577a0-ffffffff810577b1: default_apic_id_valid (STB_LOCAL)
ffffffff8105d2d0-ffffffff8105d2e1: default_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int default_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81056f80)
Location: arch/x86/include/asm/apic.h:506
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105c9f0)
Location: arch/x86/include/asm/apic.h:506
Inline: False
```
**Symbols:**

```
ffffffff81056f80-ffffffff81056f91: default_apic_id_valid (STB_LOCAL)
ffffffff8105c9f0-ffffffff8105ca01: default_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int default_apic_id_valid(int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105acd0)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8105acd0-ffffffff8105ace6: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105dcd0)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8105dcd0-ffffffff8105dce6: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81063960)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81063960-ffffffff81063976: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067020)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81067020-ffffffff81067036: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067690)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81067690-ffffffff810676a6: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106e3e0)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8106e3e0-ffffffff8106e3f6: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106f860)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8106f860-ffffffff8106f876: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81070390)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81070390-ffffffff810703a6: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8107bf30)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8107bf30-ffffffff8107bf46: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8108b1d0)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8108b1d0-ffffffff8108b1ec: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8109f430)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff8109f430-ffffffff8109f44c: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a23c0)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff810a23c0-ffffffff810a23dc: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067180)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81067180-ffffffff81067196: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81057540)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81057540-ffffffff81057556: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067630)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81067630-ffffffff81067646: default_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81068c10)
Location: arch/x86/kernel/apic/apic_common.c:43
Inline: False
```
**Symbols:**

```
ffffffff81068c10-ffffffff81068c26: default_apic_id_valid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
</li>
</ul>
</details>
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
