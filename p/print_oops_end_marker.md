# Function: <code>print_oops_end_marker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81080e80)
Location: kernel/panic.c:412
Inline: False
Direct callers:
  - kernel/panic.c:oops_exit
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81080e80-ffffffff81080ed4: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81082d00)
Location: kernel/panic.c:461
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff81082d00-ffffffff81082d54: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81087790)
Location: kernel/panic.c:491
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff81087790-ffffffff810877e4: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81084620)
Location: kernel/panic.c:493
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff81084620-ffffffff81084674: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108b000)
Location: kernel/panic.c:498
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff8108b000-ffffffff8108b054: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:487
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff8108ec1c-ffffffff8108ec2c: print_oops_end_marker.cold.10 (STB_LOCAL)
ffffffff8108e7e0-ffffffff8108e81f: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff81096a9a)
Location: kernel/panic.c:522
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff81096fbc-ffffffff81096fcc: print_oops_end_marker.cold.10 (STB_LOCAL)
ffffffff81096a70-ffffffff81096aaf: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8109b01a)
Location: kernel/panic.c:527
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff8109b568-ffffffff8109b578: print_oops_end_marker.cold (STB_LOCAL)
ffffffff8109aff0-ffffffff8109b02f: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810a153a)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff810a1a94-ffffffff810a1aa4: print_oops_end_marker.cold (STB_LOCAL)
ffffffff810a1510-ffffffff810a154f: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810a84ca)
Location: kernel/panic.c:554
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff810a88d5-ffffffff810a88e5: print_oops_end_marker.cold (STB_LOCAL)
ffffffff810a8390-ffffffff810a83cf: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a41d6)
Location: kernel/panic.c:554
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
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
In kernel/panic.c (ffffffff810a4e26)
Location: kernel/panic.c:554
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
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
In kernel/panic.c (ffffffff810b6666)
Location: kernel/panic.c:552
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
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
In kernel/panic.c (ffffffff81e53532)
Location: kernel/panic.c:580
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
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
In kernel/panic.c (ffffffff810eaad5)
Location: kernel/panic.c:631
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
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
In kernel/panic.c (ffffffff810f66b5)
Location: kernel/panic.c:631
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
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
In kernel/panic.c (ffffffff810ffa65)
Location: kernel/panic.c:635
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6690)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffff8000100f6690-ffff8000100f66e8: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c03547e0)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
c03547e0-c035483c: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c510)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
c00000000013c510-c00000000013c58c: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c2388)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffe0000c2388-ffffffe0000c23d6: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8109ae5a)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff8109b3b4-ffffffff8109b3c4: print_oops_end_marker.cold (STB_LOCAL)
ffffffff8109ae30-ffffffff8109ae6f: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8108989a)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff81089de8-ffffffff81089df8: print_oops_end_marker.cold (STB_LOCAL)
ffffffff81089870-ffffffff810898af: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8109ae0a)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff8109b364-ffffffff8109b374: print_oops_end_marker.cold (STB_LOCAL)
ffffffff8109ade0-ffffffff8109ae1f: print_oops_end_marker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_oops_end_marker();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810a2a7a)
Location: kernel/panic.c:536
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:oops_exit
```
**Symbols:**

```
ffffffff810a2fdb-ffffffff810a2feb: print_oops_end_marker.cold (STB_LOCAL)
ffffffff810a2a50-ffffffff810a2a8f: print_oops_end_marker (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
