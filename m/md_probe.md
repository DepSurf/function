# Function: <code>md_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81694d30)
Location: drivers/md/md.c:5077
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81694d30-ffffffff81694d44: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816fc39b)
Location: drivers/md/md.c:5092
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff816f5830-ffffffff816f5844: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8172c9cd)
Location: drivers/md/md.c:5126
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81726f70-ffffffff81726f84: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817452d0)
Location: drivers/md/md.c:5325
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8173f790-ffffffff8173f7b0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b74a0)
Location: drivers/md/md.c:5370
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff817b17b0-ffffffff817b17d0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818016cf)
Location: drivers/md/md.c:5387
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff817f97d0-ffffffff817f97f0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8182d8e0)
Location: drivers/md/md.c:5378
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff818257a0-ffffffff818257c0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8186f96b)
Location: drivers/md/md.c:5446
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff81867c10-ffffffff81867c30: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a1770)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff818999a0-ffffffff818999c0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81971554)
Location: drivers/md/md.c:5737
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff81968fc0-ffffffff81968fe0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196fac0)
Location: drivers/md/md.c:5771
Inline: False
Direct callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff8196fac0-ffffffff8196faef: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81952e70)
Location: drivers/md/md.c:5730
Inline: False
Direct callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff81952e70-ffffffff81952e9f: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5739
Inline: False
Direct callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff819f85c0-ffffffff819f860f: md_probe (STB_LOCAL)
ffffffff81d27b65-ffffffff81d27b79: md_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81b5e426)
Location: drivers/md/md.c:5728
Inline: True
Direct callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff81b5e3d0-ffffffff81b5e43e: md_probe (STB_LOCAL)
ffffffff81ef39bf-ffffffff81ef39d4: md_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81cfe276)
Location: drivers/md/md.c:5714
Inline: True
```
**Symbols:**

```
ffffffff81cfe220-ffffffff81cfe2b8: md_probe (STB_LOCAL)
ffffffff820a7ed1-ffffffff820a7ee6: md_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81d653e6)
Location: drivers/md/md.c:5696
Inline: True
```
**Symbols:**

```
ffffffff81d65390-ffffffff81d65428: md_probe (STB_LOCAL)
ffffffff8212927f-ffffffff82129294: md_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_probe(dev_t dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81e1c166)
Location: drivers/md/md.c:5842
Inline: True
```
**Symbols:**

```
ffffffff81e1c110-ffffffff81e1c1a8: md_probe (STB_LOCAL)
ffffffff8220ac68-ffffffff8220ac7d: md_probe.cold (STB_LOCAL)
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
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af5f3c)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffff800010aeb898-ffff800010aeb8e8: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd67a8)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
c0bcbe10-c0bcbe50: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000be25a4)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
c000000000bd8db0-c000000000bd8e08: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e85fa)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffe0006e2372-ffffffe0006e23b6: md_probe (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818475f0)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff8183f820-ffffffff8183f840: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8180ec50)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff81806e80-ffffffff81806ea0: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81896c20)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff8188ee50-ffffffff8188ee70: md_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct kobject *md_probe(dev_t dev, int *part, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818b2c00)
Location: drivers/md/md.c:5542
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
**Symbols:**

```
ffffffff818a9ba0-ffffffff818a9bc0: md_probe (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *part</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct kobject *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
