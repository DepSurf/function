# Function: <code>dax_inode</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163caa0)
Location: drivers/dax/super.c:525
Inline: False
```
**Symbols:**

```
ffffffff8163caa0-ffffffff8163caaf: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5730)
Location: drivers/dax/super.c:554
Inline: False
```
**Symbols:**

```
ffffffff816a5730-ffffffff816a573f: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1980)
Location: drivers/dax/super.c:580
Inline: False
```
**Symbols:**

```
ffffffff816e1980-ffffffff816e198f: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704da0)
Location: drivers/dax/super.c:579
Inline: False
```
**Symbols:**

```
ffffffff81704da0-ffffffff81704daf: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ec10)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff8173ec10-ffffffff8173ec1f: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762df0)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff81762df0-ffffffff81762dff: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822bb0)
Location: drivers/dax/super.c:666
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81822bb0-ffffffff81822bbf: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818318c0)
Location: drivers/dax/super.c:674
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff818318c0-ffffffff818318cf: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814af0)
Location: drivers/dax/super.c:674
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81814af0-ffffffff81814aff: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f2b0)
Location: drivers/dax/super.c:629
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff8189f2b0-ffffffff8189f2bf: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8ed0)
Location: drivers/dax/super.c:438
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff819e8ed0-ffffffff819e8ee4: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b652f0)
Location: drivers/dax/super.c:503
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81b652f0-ffffffff81b65304: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb88f0)
Location: drivers/dax/super.c:506
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81bb88f0-ffffffff81bb8904: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0cf50)
Location: drivers/dax/super.c:507
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81c0cf50-ffffffff81c0cf64: dax_inode (STB_GLOBAL)
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
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962b28)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffff800010962b28-ffff800010962b50: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a399c0)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
c0a399c0-c0a399dc: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18bd0)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
c000000000a18bd0-c000000000a18be0: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0174)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffe0005d0174-ffffffe0005d0198: dax_inode (STB_GLOBAL)
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
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817174e0)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff817174e0-ffffffff817174ef: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efa10)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
  - drivers/dax/device.c:dev_dax_probe
  - drivers/dax/device.c:dax_open
```
**Symbols:**

```
ffffffff816efa10-ffffffff816efa1f: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817562b0)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff817562b0-ffffffff817562bf: dax_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *dax_inode(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771720)
Location: drivers/dax/super.c:638
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff81771720-ffffffff8177172f: dax_inode (STB_GLOBAL)
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
