# Function: <code>kswapd_run</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2b60)
Location: mm/vmscan.c:3602
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811a2b60-ffffffff811a2c0a: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b9220)
Location: mm/vmscan.c:3586
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811b9220-ffffffff811b92ca: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c9860)
Location: mm/vmscan.c:3594
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811c9860-ffffffff811c990a: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d22e0)
Location: mm/vmscan.c:3697
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811d22e0-ffffffff811d2396: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e7780)
Location: mm/vmscan.c:3720
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811e7780-ffffffff811e7836: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3749
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8120cdac-ffffffff8120cdd3: kswapd_run.cold.59 (STB_LOCAL)
ffffffff81208d40-ffffffff81208dca: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8121ba91)
Location: mm/vmscan.c:4042
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8121fc29-ffffffff8121fc50: kswapd_run.cold.62 (STB_LOCAL)
ffffffff8121ba20-ffffffff8121baaa: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8122b73b)
Location: mm/vmscan.c:3996
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8122f3d1-ffffffff8122f3f7: kswapd_run.cold (STB_LOCAL)
ffffffff8122b6b0-ffffffff8122b742: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8123960b)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8123d561-ffffffff8123d587: kswapd_run.cold (STB_LOCAL)
ffffffff81239580-ffffffff81239612: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4046
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8126adc5-ffffffff8126adeb: kswapd_run.cold (STB_LOCAL)
ffffffff8126ac00-ffffffff8126ac92: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4044
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81be6e97-ffffffff81be6ebd: kswapd_run.cold (STB_LOCAL)
ffffffff81275640-ffffffff812756d2: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4242
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81bd8c03-ffffffff81bd8c29: kswapd_run.cold (STB_LOCAL)
ffffffff8127a960-ffffffff8127a9f2: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4434
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81cba8d4-ffffffff81cba8f3: kswapd_run.cold (STB_LOCAL)
ffffffff812b89d0-ffffffff812b8a53: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4580
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81e6c1d3-ffffffff81e6c1f0: kswapd_run.cold (STB_LOCAL)
ffffffff81314440-ffffffff813144e8: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81388530)
Location: mm/vmscan.c:7520
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81388530-ffffffff813885f8: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8214ba10)
Location: mm/vmscan.c:7884
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8214ba10-ffffffff8214bad3: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8222e4c0)
Location: mm/vmscan.c:7251
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8222e4c0-ffffffff8222e586: kswapd_run (STB_GLOBAL)
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
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102ca460)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff8000102ca460-ffff8000102ca520: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f42bc)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
```
**Symbols:**

```
c04f42bc-c04f4370: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000386ea0)
Location: mm/vmscan.c:4082
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
c000000000386ea0-c000000000386fb8: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e9536)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
```
**Symbols:**

```
ffffffe0001e9536-ffffffe0001e95ea: kswapd_run (STB_GLOBAL)
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
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81231c5b)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81235bb1-ffffffff81235bd7: kswapd_run.cold (STB_LOCAL)
ffffffff81231bd0-ffffffff81231c62: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81224d1b)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81228c15-ffffffff81228c3b: kswapd_run.cold (STB_LOCAL)
ffffffff81224c90-ffffffff81224d22: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8122f9fb)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81233951-ffffffff81233977: kswapd_run.cold (STB_LOCAL)
ffffffff8122f970-ffffffff8122fa02: kswapd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kswapd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8123ee3b)
Location: mm/vmscan.c:4082
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81242e7f-ffffffff81242ea5: kswapd_run.cold (STB_LOCAL)
ffffffff8123edb0-ffffffff8123ee42: kswapd_run (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
