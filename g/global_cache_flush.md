# Function: <code>global_cache_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8151d810)
Location: drivers/char/agp/generic.c:1316
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8151d810-ffffffff8151d83e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815705e0)
Location: drivers/char/agp/generic.c:1316
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff815705e0-ffffffff8157060e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8159cca0)
Location: drivers/char/agp/generic.c:1316
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8159cca0-ffffffff8159ccce: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815b0d60)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff815b0d60-ffffffff815b0d8e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81617900)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff81617900-ffffffff8161792e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff816521fb-ffffffff81652207: global_cache_flush.cold.18 (STB_LOCAL)
ffffffff81651400-ffffffff81651426: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff816703cf-ffffffff816703db: global_cache_flush.cold.17 (STB_LOCAL)
ffffffff8166f5d0-ffffffff8166f5f6: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816a5110)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff816a5110-ffffffff816a512e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816c7e40)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff816c7e40-ffffffff816c7e5e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8177c5e0)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8177c5e0-ffffffff8177c5fe: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81795730)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81795730-ffffffff8179574e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff817783e0)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff817783e0-ffffffff81778407: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff817fde80)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff817fde80-ffffffff817fdea7: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8193d3d0)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8193d3d0-ffffffff8193d406: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81a9e250)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81a9e250-ffffffff81a9e286: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81ae9bf0)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81ae9bf0-ffffffff81ae9c26: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81b3d080)
Location: drivers/char/agp/generic.c:1309
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81b3d080-ffffffff81b3d0b6: global_cache_flush (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (c000000000955510)
Location: drivers/char/agp/generic.c:1312
Inline: False
```
**Symbols:**

```
c000000000955510-c000000000955554: global_cache_flush (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8168d890)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8168d890-ffffffff8168d8ae: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166b280)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8166b280-ffffffff8166b29e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816bbb00)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff816bbb00-ffffffff816bbb1e: global_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void global_cache_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816d60d0)
Location: drivers/char/agp/generic.c:1312
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:amd64_insert_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff816d60d0-ffffffff816d60ee: global_cache_flush (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
