# Function: <code>kill_dax</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163d350)
Location: drivers/dax/super.c:305
Inline: True
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8163d350-ffffffff8163d3c7: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a6090)
Location: drivers/dax/super.c:331
Inline: True
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff816a6090-ffffffff816a6107: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1e40)
Location: drivers/dax/super.c:357
Inline: True
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff816e1e40-ffffffff816e1eb6: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81705260)
Location: drivers/dax/super.c:356
Inline: True
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81705260-ffffffff817052d6: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f0d0)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8173f0d0-ffffffff8173f13b: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817632e0)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff817632e0-ffffffff8176334b: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81823180)
Location: drivers/dax/super.c:429
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81823180-ffffffff818231ee: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831ec0)
Location: drivers/dax/super.c:437
Inline: True
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81831ec0-ffffffff81831f2e: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818155f0)
Location: drivers/dax/super.c:437
Inline: True
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff818155f0-ffffffff8181565e: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189fd90)
Location: drivers/dax/super.c:424
Inline: True
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8189fd90-ffffffff8189fdfe: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e9280)
Location: drivers/dax/super.c:275
Inline: True
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff819e9280-ffffffff819e92b1: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65b90)
Location: drivers/dax/super.c:320
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81b65b90-ffffffff81b65c09: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb91b0)
Location: drivers/dax/super.c:323
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81bb91b0-ffffffff81bb9229: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d810)
Location: drivers/dax/super.c:323
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81c0d810-ffffffff81c0d88c: kill_dax (STB_GLOBAL)
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
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962f58)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffff800010962f58-ffff800010963030: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39f10)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c0a39f10-c0a39f9c: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a192a0)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c000000000a192a0-c000000000a19380: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0678)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffe0005d0678-ffffffe0005d071c: kill_dax (STB_GLOBAL)
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
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817179d0)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff817179d0-ffffffff81717a3b: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816eff00)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_release_disk
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff816eff00-ffffffff816eff6b: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817567a0)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff817567a0-ffffffff8175680b: kill_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kill_dax(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771b90)
Location: drivers/dax/super.c:408
Inline: True
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81771b90-ffffffff81771bf9: kill_dax (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
