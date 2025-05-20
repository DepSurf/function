# Function: <code>scsi_alloc_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b3140)
Location: drivers/scsi/scsi_scan.c:411
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
```
**Symbols:**

```
ffffffff815b3140-ffffffff815b342f: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160b5a0)
Location: drivers/scsi/scsi_scan.c:417
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8160b5a0-ffffffff8160b887: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8163ae40)
Location: drivers/scsi/scsi_scan.c:415
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8163ae40-ffffffff8163b127: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164f520)
Location: drivers/scsi/scsi_scan.c:417
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8164f520-ffffffff8164f7f8: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b87c0)
Location: drivers/scsi/scsi_scan.c:418
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff816b87c0-ffffffff816b8af4: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:418
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff816f3910-ffffffff816f3c1a: scsi_alloc_target (STB_LOCAL)
ffffffff816f5f32-ffffffff816f5f4d: scsi_alloc_target.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff817174b0-ffffffff817177a8: scsi_alloc_target (STB_LOCAL)
ffffffff81718842-ffffffff8171885d: scsi_alloc_target.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff817521a0-ffffffff8175242d: scsi_alloc_target (STB_LOCAL)
ffffffff81753f01-ffffffff81753f45: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81776420-ffffffff817766ad: scsi_alloc_target (STB_LOCAL)
ffffffff81778181-ffffffff817781c5: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:409
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81839720-ffffffff818399b5: scsi_alloc_target (STB_LOCAL)
ffffffff8183b102-ffffffff8183b149: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:409
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81849fa0-ffffffff8184a235: scsi_alloc_target (STB_LOCAL)
ffffffff81c16985-ffffffff81c169cc: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8182d720-ffffffff8182d9c6: scsi_alloc_target (STB_LOCAL)
ffffffff81c08660-ffffffff81c08692: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:433
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff818b9170-ffffffff818b9416: scsi_alloc_target (STB_LOCAL)
ffffffff81d0c716-ffffffff81d0c748: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:491
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81a04de0-ffffffff81a050ef: scsi_alloc_target (STB_LOCAL)
ffffffff81ed5648-ffffffff81ed5677: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b83a90)
Location: drivers/scsi/scsi_scan.c:491
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81b83a90-ffffffff81b83dc4: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd77f0)
Location: drivers/scsi/scsi_scan.c:491
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81bd77f0-ffffffff81bd7b29: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2c490)
Location: drivers/scsi/scsi_scan.c:491
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81c2c490-ffffffff81c2c7c9: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097bad8)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffff80001097bad8-ffff80001097bdcc: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4e900)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
c0a4e900-c0a4eb88: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a354b0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
c000000000a354b0-c000000000a35844: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e2942)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffe0005e2942-ffffffe0005e2baa: scsi_alloc_target (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8172ab10-ffffffff8172ad9d: scsi_alloc_target (STB_LOCAL)
ffffffff8172c871-ffffffff8172c8b5: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81703f30-ffffffff817041bd: scsi_alloc_target (STB_LOCAL)
ffffffff81705c91-ffffffff81705cd5: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff817698e0-ffffffff81769b6d: scsi_alloc_target (STB_LOCAL)
ffffffff8176b641-ffffffff8176b685: scsi_alloc_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct scsi_target *scsi_alloc_target(struct device *parent, int channel, uint id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81785030-ffffffff817852bd: scsi_alloc_target (STB_LOCAL)
ffffffff81786d81-ffffffff81786dc5: scsi_alloc_target.cold (STB_LOCAL)
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
