# Function: <code>sync_file_ioctl_fence_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff815fd3d8)
Location: drivers/dma-buf/sync_file.c:313
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8162b808)
Location: drivers/dma-buf/sync_file.c:389
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816411c0)
Location: drivers/dma-buf/sync_file.c:404
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816411c0-ffffffff81641439: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816a9fb0)
Location: drivers/dma-buf/sync_file.c:406
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816a9fb0-ffffffff816aa245: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816e64c0)
Location: drivers/dma-buf/sync_file.c:406
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816e64c0-ffffffff816e6745: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81709850)
Location: drivers/dma-buf/sync_file.c:406
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81709850-ffffffff81709ad3: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81745040)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81745040-ffffffff817452c9: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff817691f0)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff817691f0-ffffffff8176944c: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8182b3f0)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8182b3f0-ffffffff8182b5c9: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8183c240)
Location: drivers/dma-buf/sync_file.c:397
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8183c240-ffffffff8183c419: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8181f330)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8181f330-ffffffff8181f505: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff818a99d0)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff818a99d0-ffffffff818a9ba5: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff819f3d40)
Location: drivers/dma-buf/sync_file.c:389
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff819f3d40-ffffffff819f40e2: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81b71220)
Location: drivers/dma-buf/sync_file.c:282
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81b71220-ffffffff81b71444: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81bc4a60)
Location: drivers/dma-buf/sync_file.c:282
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81bc4a60-ffffffff81bc4c86: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81c192f0)
Location: drivers/dma-buf/sync_file.c:279
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81c192f0-ffffffff81c19516: sync_file_ioctl_fence_info (STB_LOCAL)
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
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffff80001096a870)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffff80001096a870-ffff80001096aaf4: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c0a405b4)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
c0a405b4-c0a4092c: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c000000000a22fe0)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
c000000000a22fe0-c000000000a23344: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffe0005d5da6)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffe0005d5da6-ffffffe0005d5f9c: sync_file_ioctl_fence_info (STB_LOCAL)
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
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8171d8e0)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8171d8e0-ffffffff8171db3c: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816f6d40)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816f6d40-ffffffff816f6f9c: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8175c6b0)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8175c6b0-ffffffff8175c90c: sync_file_ioctl_fence_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81777d50)
Location: drivers/dma-buf/sync_file.c:398
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81777d50-ffffffff81777fac: sync_file_ioctl_fence_info (STB_LOCAL)
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
