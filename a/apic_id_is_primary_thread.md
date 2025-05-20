# Function: <code>apic_id_is_primary_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105d640)
Location: arch/x86/kernel/apic/apic.c:2201
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff8105d640-ffffffff8105d66f: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810632d0)
Location: arch/x86/kernel/apic/apic.c:2209
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff810632d0-ffffffff810632ff: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066970)
Location: arch/x86/kernel/apic/apic.c:2298
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81066970-ffffffff8106699e: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066fe0)
Location: arch/x86/kernel/apic/apic.c:2355
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81066fe0-ffffffff8106700e: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106dbf0)
Location: arch/x86/kernel/apic/apic.c:2316
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff8106dbf0-ffffffff8106dc1e: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f390)
Location: arch/x86/kernel/apic/apic.c:2347
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff8106f390-ffffffff8106f3be: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106fec0)
Location: arch/x86/kernel/apic/apic.c:2355
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff8106fec0-ffffffff8106feee: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2352
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81c9dbad-ffffffff81c9dbcc: apic_id_is_primary_thread.cold (STB_LOCAL)
ffffffff8107b910-ffffffff8107b956: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2360
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81e4d033-ffffffff81e4d052: apic_id_is_primary_thread.cold (STB_LOCAL)
ffffffff8108aae0-ffffffff8108ab3e: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2394
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff82053c55-ffffffff82053c74: apic_id_is_primary_thread.cold (STB_LOCAL)
ffffffff8109ebd0-ffffffff8109ec2e: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066ad0)
Location: arch/x86/kernel/apic/apic.c:2355
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81066ad0-ffffffff81066afe: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056ea0)
Location: arch/x86/kernel/apic/apic.c:2355
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81056ea0-ffffffff81056ece: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066f80)
Location: arch/x86/kernel/apic/apic.c:2355
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81066f80-ffffffff81066fae: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool apic_id_is_primary_thread(unsigned int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81068560)
Location: arch/x86/kernel/apic/apic.c:2355
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_is_primary_thread
```
**Symbols:**

```
ffffffff81068560-ffffffff8106858e: apic_id_is_primary_thread (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
