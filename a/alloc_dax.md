# Function: <code>alloc_dax</code>

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
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163cba0)
Location: drivers/dax/super.c:436
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8163cba0-ffffffff8163cda1: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5870)
Location: drivers/dax/super.c:465
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff816a5870-ffffffff816a5a71: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1c40)
Location: drivers/dax/super.c:491
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff816e1c40-ffffffff816e1e40: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81705060)
Location: drivers/dax/super.c:490
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81705060-ffffffff81705260: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173eeb0)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8173eeb0-ffffffff8173f0cc: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763090)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81763090-ffffffff817632ac: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822ec0)
Location: drivers/dax/super.c:567
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81822ec0-ffffffff81823145: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831c00)
Location: drivers/dax/super.c:575
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81831c00-ffffffff81831e85: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814e30)
Location: drivers/dax/super.c:575
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81814e30-ffffffff818150b5: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f5a0)
Location: drivers/dax/super.c:562
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8189f5a0-ffffffff8189f822: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8ff0)
Location: drivers/dax/super.c:387
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff819e8ff0-ffffffff819e913c: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65620)
Location: drivers/dax/super.c:439
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81b65620-ffffffff81b6576c: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8c40)
Location: drivers/dax/super.c:442
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81bb8c40-ffffffff81bb8d8c: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const struct dax_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d2a0)
Location: drivers/dax/super.c:443
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81c0d2a0-ffffffff81c0d3ec: alloc_dax (STB_GLOBAL)
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
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963890)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff800010963890-ffff800010963b28: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39aac)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
**Symbols:**

```
c0a39aac-c0a39cec: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18ca0)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c000000000a18ca0-c000000000a18fb8: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0442)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe0005d0442-ffffffe0005d063c: alloc_dax (STB_GLOBAL)
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
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717780)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81717780-ffffffff8171799c: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efcb0)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff816efcb0-ffffffff816efecc: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756550)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81756550-ffffffff8175676c: alloc_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dax_device *alloc_dax(void *private, const char *__host, const struct dax_operations *ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817717b0)
Location: drivers/dax/super.c:546
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff817717b0-ffffffff817719bb: alloc_dax (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char *__host</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>private, __host, ops, flags</code> ➡️ <code>private, ops</code>
</li>
</ul>
</details>
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
