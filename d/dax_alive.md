# Function: <code>dax_alive</code>

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
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163ce2a)
Location: drivers/dax/super.c:287
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/dax/super.c:dax_direct_access
```
**Symbols:**

```
ffffffff8163ca20-ffffffff8163ca35: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5afa)
Location: drivers/dax/super.c:313
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/dax/super.c:dax_direct_access
```
**Symbols:**

```
ffffffff816a56b0-ffffffff816a56c5: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1f1a)
Location: drivers/dax/super.c:339
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff816e1900-ffffffff816e1915: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8170533a)
Location: drivers/dax/super.c:338
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff81704d20-ffffffff81704d35: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f1cb)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff8173eb70-ffffffff8173eb85: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817633ab)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81762d50-ffffffff81762d65: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8182324b)
Location: drivers/dax/super.c:411
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
**Symbols:**

```
ffffffff81822b30-ffffffff81822b45: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831f8b)
Location: drivers/dax/super.c:419
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
**Symbols:**

```
ffffffff81831840-ffffffff81831855: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818156bb)
Location: drivers/dax/super.c:419
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
**Symbols:**

```
ffffffff81814a70-ffffffff81814a85: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f1b5)
Location: drivers/dax/super.c:411
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff8189f230-ffffffff8189f245: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8ce5)
Location: drivers/dax/super.c:262
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/dax/super.c:dax_direct_access
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff819e8e30-ffffffff819e8e4b: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65b0d)
Location: drivers/dax/super.c:307
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/dax/super.c:dax_direct_access
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff81b65440-ffffffff81b6545b: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb912d)
Location: drivers/dax/super.c:310
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/dax/super.c:dax_direct_access
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff81bb8a40-ffffffff81bb8a5b: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d78d)
Location: drivers/dax/super.c:310
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:dax_zero_page_range
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/dax/super.c:dax_direct_access
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff81c0d0a0-ffffffff81c0d0bb: dax_alive (STB_GLOBAL)
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
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff8000109630b8)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffff800010962a58-ffff800010962a84: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a3c0)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
c0a3992c-c0a3994c: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a195a8)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
c000000000a18b20-c000000000a18b34: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0784)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffe0005d009c-ffffffe0005d00c2: dax_alive (STB_GLOBAL)
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
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717a9b)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81717440-ffffffff81717455: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816effcb)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - drivers/dax/device.c:check_vma
```
**Symbols:**

```
ffffffff816ef970-ffffffff816ef985: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8175686b)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81756210-ffffffff81756225: dax_alive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool dax_alive(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771ccb)
Location: drivers/dax/super.c:390
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81771680-ffffffff81771695: dax_alive (STB_GLOBAL)
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
