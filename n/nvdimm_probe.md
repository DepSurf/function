# Function: <code>nvdimm_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff815994f0)
Location: drivers/nvdimm/dimm.c:24
Inline: False
```
**Symbols:**

```
ffffffff815994f0-ffffffff81599684: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff815eefd0)
Location: drivers/nvdimm/dimm.c:24
Inline: False
```
**Symbols:**

```
ffffffff815eefd0-ffffffff815ef15c: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff8161c150)
Location: drivers/nvdimm/dimm.c:24
Inline: True
```
**Symbols:**

```
ffffffff8161c150-ffffffff8161c32b: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81630190)
Location: drivers/nvdimm/dimm.c:24
Inline: True
```
**Symbols:**

```
ffffffff81630190-ffffffff81630372: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff816989b0)
Location: drivers/nvdimm/dimm.c:24
Inline: True
```
**Symbols:**

```
ffffffff816989b0-ffffffff81698ba2: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff816d4c20)
Location: drivers/nvdimm/dimm.c:24
Inline: True
```
**Symbols:**

```
ffffffff816d4c20-ffffffff816d4e32: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff816f6960)
Location: drivers/nvdimm/dimm.c:24
Inline: True
```
**Symbols:**

```
ffffffff816f6960-ffffffff816f6b40: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff817302a5)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81730260-ffffffff81730418: nvdimm_probe (STB_LOCAL)
ffffffff81730437-ffffffff81730450: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81754335)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff817542f0-ffffffff817544a8: nvdimm_probe (STB_LOCAL)
ffffffff817544c7-ffffffff817544e0: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81812ef0)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81812ef0-ffffffff8181307d: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff81813080-ffffffff818130ca: nvdimm_probe (STB_LOCAL)
ffffffff818130e7-ffffffff81813103: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81822120)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81822120-ffffffff818222ad: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff818222b0-ffffffff818222fa: nvdimm_probe (STB_LOCAL)
ffffffff81c15b2d-ffffffff81c15b49: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81805430)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81805430-ffffffff818055bd: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff818055c0-ffffffff81805607: nvdimm_probe (STB_LOCAL)
ffffffff81c07885-ffffffff81c078a1: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff8188fac0)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff8188fac0-ffffffff8188fc47: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff8188fc50-ffffffff8188fc97: nvdimm_probe (STB_LOCAL)
ffffffff81d0af4f-ffffffff81d0af6b: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff819d9500)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff819d9500-ffffffff819d96a9: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff819d96b0-ffffffff819d970a: nvdimm_probe (STB_LOCAL)
ffffffff81ed33fa-ffffffff81ed3416: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81b545e0)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81b545e0-ffffffff81b54789: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff81b547a0-ffffffff81b5481d: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81ba7b30)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81ba7b30-ffffffff81ba7cd9: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff81ba7cf0-ffffffff81ba7d6d: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81bfbe90)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81bfbe90-ffffffff81bfc068: nvdimm_probe.part.0 (STB_LOCAL)
ffffffff81bfc080-ffffffff81bfc0fd: nvdimm_probe (STB_LOCAL)
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
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffff800010954e70)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffff800010954e70-ffff80001095504c: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (c000000000a02ac0)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
c000000000a02ac0-c000000000a02d98: nvdimm_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffe0005c444e)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffe0005c444e-ffffffe0005c4636: nvdimm_probe (STB_LOCAL)
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
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81708a25)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff817089e0-ffffffff81708b98: nvdimm_probe (STB_LOCAL)
ffffffff81708bb7-ffffffff81708bd0: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff816dc4a5)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff816dc460-ffffffff816dc618: nvdimm_probe (STB_LOCAL)
ffffffff816dc637-ffffffff816dc650: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff817477f5)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff817477b0-ffffffff81747968: nvdimm_probe (STB_LOCAL)
ffffffff81747987-ffffffff817479a0: nvdimm_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvdimm_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81762c35)
Location: drivers/nvdimm/dimm.c:16
Inline: True
```
**Symbols:**

```
ffffffff81762bf0-ffffffff81762da8: nvdimm_probe (STB_LOCAL)
ffffffff81762dc7-ffffffff81762de0: nvdimm_probe.cold (STB_LOCAL)
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
