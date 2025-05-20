# Function: <code>sync_file_get_name</code>

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
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81641130)
Location: drivers/dma-buf/sync_file.c:140
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81641130-ffffffff816411b7: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816a9f10)
Location: drivers/dma-buf/sync_file.c:140
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff816a9f10-ffffffff816a9fa3: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816e6420)
Location: drivers/dma-buf/sync_file.c:140
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff816e6420-ffffffff816e64b7: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff817097b0)
Location: drivers/dma-buf/sync_file.c:140
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff817097b0-ffffffff81709847: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81744fa0)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81744fa0-ffffffff81745039: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81769150)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81769150-ffffffff817691e9: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8182b350)
Location: drivers/dma-buf/sync_file.c:131
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8182b350-ffffffff8182b3e9: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (0)
Location: drivers/dma-buf/sync_file.c:131
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81c16235-ffffffff81c1624d: sync_file_get_name.cold (STB_LOCAL)
ffffffff8183c0d0-ffffffff8183c231: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (0)
Location: drivers/dma-buf/sync_file.c:131
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81c07f23-ffffffff81c07f3b: sync_file_get_name.cold (STB_LOCAL)
ffffffff8181f1c0-ffffffff8181f321: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (0)
Location: drivers/dma-buf/sync_file.c:131
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81d0bd0c-ffffffff81d0bd24: sync_file_get_name.cold (STB_LOCAL)
ffffffff818a9860-ffffffff818a99c1: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (0)
Location: drivers/dma-buf/sync_file.c:132
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81ed4b6c-ffffffff81ed4b84: sync_file_get_name.cold (STB_LOCAL)
ffffffff819f3bd0-ffffffff819f3d31: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81b71120)
Location: drivers/dma-buf/sync_file.c:132
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81b71120-ffffffff81b71207: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81bc4960)
Location: drivers/dma-buf/sync_file.c:132
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81bc4960-ffffffff81bc4a47: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81c191f0)
Location: drivers/dma-buf/sync_file.c:132
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81c191f0-ffffffff81c192d7: sync_file_get_name (STB_GLOBAL)
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
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffff80001096a7c0)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffff80001096a7c0-ffff80001096a86c: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c0a4050c)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
c0a4050c-c0a405b4: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c000000000a22ee0)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
c000000000a22ee0-c000000000a22fd4: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffe0005d5d22)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffe0005d5d22-ffffffe0005d5da6: sync_file_get_name (STB_GLOBAL)
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
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8171d840)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8171d840-ffffffff8171d8d9: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816f6ca0)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff816f6ca0-ffffffff816f6d39: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8175c610)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff8175c610-ffffffff8175c6a9: sync_file_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *sync_file_get_name(struct sync_file *sync_file, char *buf, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81777cb0)
Location: drivers/dma-buf/sync_file.c:131
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_debug.c:sync_print_sync_file
```
**Symbols:**

```
ffffffff81777cb0-ffffffff81777d49: sync_file_get_name (STB_GLOBAL)
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
