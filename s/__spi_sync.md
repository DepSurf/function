# Function: <code>__spi_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message, int bus_locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e81e0)
Location: drivers/spi/spi.c:2344
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_write_then_read
```
**Symbols:**

```
ffffffff815e81e0-ffffffff815e840c: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81646ae0)
Location: drivers/spi/spi.c:2821
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff81646ae0-ffffffff81646cc8: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81677bd0)
Location: drivers/spi/spi.c:2848
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff81677bd0-ffffffff81677db8: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168c2b0)
Location: drivers/spi/spi.c:3011
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff8168c2b0-ffffffff8168c498: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f5c60)
Location: drivers/spi/spi.c:3081
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff816f5c60-ffffffff816f5e4b: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81733700)
Location: drivers/spi/spi.c:3081
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff81733700-ffffffff817338eb: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81756170)
Location: drivers/spi/spi.c:3180
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff81756170-ffffffff8175635b: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81792220)
Location: drivers/spi/spi.c:3409
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff81792220-ffffffff81792409: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b5df0)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff817b5df0-ffffffff817b5fd9: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187cbc0)
Location: drivers/spi/spi.c:3703
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff8187cbc0-ffffffff8187ce0c: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188b570)
Location: drivers/spi/spi.c:3799
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff8188b570-ffffffff8188b7b2: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186dee0)
Location: drivers/spi/spi.c:3846
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff8186dee0-ffffffff8186e119: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fdf80)
Location: drivers/spi/spi.c:3904
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff818fdf80-ffffffff818fe1b6: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4f6f0)
Location: drivers/spi/spi.c:3905
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff81a4f6f0-ffffffff81a4f93c: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:4166
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff81bd6fb0-ffffffff81bd7314: __spi_sync (STB_LOCAL)
ffffffff8209d33c-ffffffff8209d396: __spi_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:4221
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff81c2d9e0-ffffffff81c2dd44: __spi_sync (STB_LOCAL)
ffffffff8211e1f9-ffffffff8211e253: __spi_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:4383
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi.c:spi_sync_locked
```
**Symbols:**

```
ffffffff81ce03d0-ffffffff81ce079a: __spi_sync (STB_LOCAL)
ffffffff821ff776-ffffffff821ff7e4: __spi_sync.cold (STB_LOCAL)
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
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c9788)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffff8000109c9788-ffff8000109c99f8: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab3240)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
c0ab3240-c0ab348c: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8b3d0)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
c000000000a8b3d0-c000000000a8b69c: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000619866)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffe000619866-ffffffe000619a44: __spi_sync (STB_LOCAL)
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
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8177a8d0)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff8177a8d0-ffffffff8177aab9: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8175a680)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff8175a680-ffffffff8175a869: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817aac70)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff817aac70-ffffffff817aae59: __spi_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c4bf0)
Location: drivers/spi/spi.c:3413
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_sync_locked
  - drivers/spi/spi.c:spi_sync
```
**Symbols:**

```
ffffffff817c4bf0-ffffffff817c4dee: __spi_sync (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int bus_locked</code>
</li>
</ul>
</details>
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
