# Function: <code>__frontswap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff811d7710)
Location: mm/frontswap.c:187
Inline: True
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff811d7710-ffffffff811d776e: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff811f5590)
Location: mm/frontswap.c:191
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff811f5590-ffffffff811f55ea: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812060c0)
Location: mm/frontswap.c:191
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff812060c0-ffffffff8120611a: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81211870)
Location: mm/frontswap.c:191
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff81211870-ffffffff812118b7: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8122c200)
Location: mm/frontswap.c:191
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapon
```
**Symbols:**

```
ffffffff8122c200-ffffffff8122c251: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8124ee90)
Location: mm/frontswap.c:191
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8124ee90-ffffffff8124eee1: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81263370)
Location: mm/frontswap.c:191
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81263370-ffffffff812633c1: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/frontswap.c (0)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8127e990-ffffffff8127e9a3: __frontswap_init.cold (STB_LOCAL)
ffffffff8127e2d0-ffffffff8127e31e: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8128dd20)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8128dd20-ffffffff8128dd71: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812c0800)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812c0800-ffffffff812c0851: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812cc220)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812cc220-ffffffff812cc271: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812d2dd0)
Location: mm/frontswap.c:194
Inline: False
Direct callers:
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812d2dd0-ffffffff812d2e21: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81318820)
Location: mm/frontswap.c:194
Inline: False
Direct callers:
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff81318820-ffffffff81318871: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffff80001032a0b0)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffff80001032a0b0-ffff80001032a120: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (c054090c)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
c054090c-c0540984: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (c0000000004011f0)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
c0000000004011f0-c000000000401298: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffe000229550)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffe000229550-ffffffe0002295b0: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81286300)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81286300-ffffffff81286351: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81278160)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81278160-ffffffff812781b1: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81284110)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81284110-ffffffff81284161: __frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81293df0)
Location: mm/frontswap.c:190
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81293df0-ffffffff81293e41: __frontswap_init (STB_GLOBAL)
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
