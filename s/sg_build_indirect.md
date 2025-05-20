# Function: <code>sg_build_indirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff815c4880)
Location: drivers/scsi/sg.c:1824
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff815c4880-ffffffff815c4be3: sg_build_indirect.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161d080)
Location: drivers/scsi/sg.c:1825
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff8161d080-ffffffff8161d3c9: sg_build_indirect.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164dc80)
Location: drivers/scsi/sg.c:1822
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff8164dc80-ffffffff8164dfc9: sg_build_indirect.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816625a0)
Location: drivers/scsi/sg.c:1850
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff816625a0-ffffffff81662904: sg_build_indirect.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816cbbf0)
Location: drivers/scsi/sg.c:1849
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff816cbbf0-ffffffff816cbf54: sg_build_indirect.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81708520)
Location: drivers/scsi/sg.c:1882
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff81708520-ffffffff81708888: sg_build_indirect.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8172aa50)
Location: drivers/scsi/sg.c:1873
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff8172aa50-ffffffff8172ad77: sg_build_indirect.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81766170)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff81766170-ffffffff8176649b: sg_build_indirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8178a160)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff8178a160-ffffffff8178a48b: sg_build_indirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184e8f0)
Location: drivers/scsi/sg.c:1898
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff8184e8f0-ffffffff8184ec0c: sg_build_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185f260)
Location: drivers/scsi/sg.c:1891
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff8185f260-ffffffff8185f58a: sg_build_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818417e0)
Location: drivers/scsi/sg.c:1889
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff818417e0-ffffffff81841ae4: sg_build_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1858
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff818ce470-ffffffff818ce771: sg_build_indirect (STB_LOCAL)
ffffffff81d0d43d-ffffffff81d0d45c: sg_build_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1876
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81a19cf0-ffffffff81a1a071: sg_build_indirect (STB_LOCAL)
ffffffff81ed61f0-ffffffff81ed6240: sg_build_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1859
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81b9adf0-ffffffff81b9b171: sg_build_indirect (STB_LOCAL)
ffffffff8209c35d-ffffffff8209c3ad: sg_build_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1870
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81bf12b0-ffffffff81bf161e: sg_build_indirect (STB_LOCAL)
ffffffff8211d28d-ffffffff8211d2cd: sg_build_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:1869
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81c46b70-ffffffff81c46ede: sg_build_indirect (STB_LOCAL)
ffffffff821fb2c5-ffffffff821fb305: sg_build_indirect.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffff80001098f138)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffff80001098f138-ffff80001098f46c: sg_build_indirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c0a631d0)
Location: drivers/scsi/sg.c:1868
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
c0a631d0-c0a634f0: sg_build_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c000000000a53bc0)
Location: drivers/scsi/sg.c:1868
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
c000000000a53bc0-c000000000a5403c: sg_build_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sg_build_indirect(Sg_scatter_hold *schp, Sg_fd *sfp, int buff_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f4ba4)
Location: drivers/scsi/sg.c:1868
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffe0005f4ba4-ffffffe0005f4e96: sg_build_indirect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8173e850)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff8173e850-ffffffff8173eb7b: sg_build_indirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff817204f0)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff817204f0-ffffffff8172081b: sg_build_indirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8177efe0)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff8177efe0-ffffffff8177f30b: sg_build_indirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81798de0)
Location: drivers/scsi/sg.c:1868
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_build_reserve
```
**Symbols:**

```
ffffffff81798de0-ffffffff8179910b: sg_build_indirect.isra.0 (STB_LOCAL)
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
