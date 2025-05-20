# Function: <code>calipso_doi_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8186f230)
Location: net/ipv6/calipso.c:545
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883340)
Location: net/netlabel/netlabel_calipso.c:506
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff8186f230-ffffffff8186f2bc: calipso_doi_walk (STB_LOCAL)
ffffffff81883930-ffffffff81883950: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a21a0)
Location: net/ipv6/calipso.c:545
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7be0)
Location: net/netlabel/netlabel_calipso.c:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff818a21a0-ffffffff818a222c: calipso_doi_walk (STB_LOCAL)
ffffffff818b81d0-ffffffff818b81f0: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c8820)
Location: net/ipv6/calipso.c:545
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de4d0)
Location: net/netlabel/netlabel_calipso.c:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff818c8820-ffffffff818c88ab: calipso_doi_walk (STB_LOCAL)
ffffffff818deac0-ffffffff818deae0: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194bdf0)
Location: net/ipv6/calipso.c:545
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819640c0)
Location: net/netlabel/netlabel_calipso.c:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff8194bdf0-ffffffff8194be7d: calipso_doi_walk (STB_LOCAL)
ffffffff81964730-ffffffff81964756: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a5130)
Location: net/ipv6/calipso.c:545
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bd960)
Location: net/netlabel/netlabel_calipso.c:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff819a5130-ffffffff819a51bd: calipso_doi_walk (STB_LOCAL)
ffffffff819bdfd0-ffffffff819bdff6: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dbbc0)
Location: net/ipv6/calipso.c:545
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4b10)
Location: net/netlabel/netlabel_calipso.c:509
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff819dbbc0-ffffffff819dbc4d: calipso_doi_walk (STB_LOCAL)
ffffffff819f5170-ffffffff819f5196: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4a7c0)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a63fc0)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81a4a7c0-ffffffff81a4a850: calipso_doi_walk (STB_LOCAL)
ffffffff81a64640-ffffffff81a64666: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a81390)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ab50)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81a81390-ffffffff81a81420: calipso_doi_walk (STB_LOCAL)
ffffffff81a9b1c0-ffffffff81a9b1e6: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7c0a0)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b968de)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81b7c0a0-ffffffff81b7c137: calipso_doi_walk (STB_LOCAL)
ffffffff81b96a20-ffffffff81b96a46: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8b1c0)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba654e)
Location: net/netlabel/netlabel_calipso.c:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81b8b1c0-ffffffff81b8b264: calipso_doi_walk (STB_LOCAL)
ffffffff81ba6690-ffffffff81ba66b6: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7a020)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b956de)
Location: net/netlabel/netlabel_calipso.c:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81b7a020-ffffffff81b7a0bb: calipso_doi_walk (STB_LOCAL)
ffffffff81b95820-ffffffff81b95846: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c44ce0)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61f0e)
Location: net/netlabel/netlabel_calipso.c:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81c44ce0-ffffffff81c44d7b: calipso_doi_walk (STB_LOCAL)
ffffffff81c62050-ffffffff81c62076: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de3d30)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04588)
Location: net/netlabel/netlabel_calipso.c:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81de3d30-ffffffff81de3dd8: calipso_doi_walk (STB_LOCAL)
ffffffff81e04720-ffffffff81e0475a: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb6400)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9598)
Location: net/netlabel/netlabel_calipso.c:498
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81fb6400-ffffffff81fb64a8: calipso_doi_walk (STB_LOCAL)
ffffffff81fd9790-ffffffff81fd97ca: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff82016b10)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82055268)
Location: net/netlabel/netlabel_calipso.c:498
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff82016b10-ffffffff82016bb8: calipso_doi_walk (STB_LOCAL)
ffffffff82055460-ffffffff8205549a: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e5ab0)
Location: net/ipv6/calipso.c:527
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127b88)
Location: net/netlabel/netlabel_calipso.c:501
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff820e5ab0-ffffffff820e5b58: calipso_doi_walk (STB_LOCAL)
ffffffff82127d80-ffffffff82127dba: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4caa8)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a750)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffff800010d4caa8-ffff800010d4cb58: calipso_doi_walk (STB_LOCAL)
ffff800010d6af00-ffff800010d6af5c: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4ddd4)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e68cd4)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
c0e4ddd4-c0e4de64: calipso_doi_walk (STB_LOCAL)
c0e69430-c0e6946c: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e833b0)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7a4c)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
c000000000e833b0-c000000000e834b8: calipso_doi_walk (STB_LOCAL)
c000000000ea8480-c000000000ea84d8: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe00088586c)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d32a)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffe00088586c-ffffffe0008858f0: calipso_doi_walk (STB_LOCAL)
ffffffe00089d862-ffffffe00089d8a8: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a20a20)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a39ee0)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81a20a20-ffffffff81a20ab0: calipso_doi_walk (STB_LOCAL)
ffffffff81a3a550-ffffffff81a3a576: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dd7e0)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6b00)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff819dd7e0-ffffffff819dd870: calipso_doi_walk (STB_LOCAL)
ffffffff819f7170-ffffffff819f7196: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8b4a0)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5d90)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81a8b4a0-ffffffff81a8b530: calipso_doi_walk (STB_LOCAL)
ffffffff81aa6400-ffffffff81aa6426: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_walk(u32 *skip_cnt, int (*callback)(struct calipso_doi *, void *), void *cb_arg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a983b0)
Location: net/ipv6/calipso.c:531
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2130)
Location: net/netlabel/netlabel_calipso.c:496
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall
```
**Symbols:**

```
ffffffff81a983b0-ffffffff81a98450: calipso_doi_walk (STB_LOCAL)
ffffffff81ab27a0-ffffffff81ab27c6: calipso_doi_walk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
