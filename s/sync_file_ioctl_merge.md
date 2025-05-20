# Function: <code>sync_file_ioctl_merge</code>

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
In drivers/dma-buf/sync_file.c (ffffffff815fd53c)
Location: drivers/dma-buf/sync_file.c:244
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
In drivers/dma-buf/sync_file.c (ffffffff8162b98e)
Location: drivers/dma-buf/sync_file.c:320
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816414b1)
Location: drivers/dma-buf/sync_file.c:331
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816aa2c1)
Location: drivers/dma-buf/sync_file.c:331
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816e67bf)
Location: drivers/dma-buf/sync_file.c:331
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81709b4f)
Location: drivers/dma-buf/sync_file.c:331
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8174533f)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff817694bf)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int sync_file_ioctl_merge(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8182b1e0)
Location: drivers/dma-buf/sync_file.c:323
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8182b1e0-ffffffff8182b34d: sync_file_ioctl_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sync_file_ioctl_merge(struct sync_file *sync_file, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8183bf60)
Location: drivers/dma-buf/sync_file.c:322
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8183bf60-ffffffff8183c0cd: sync_file_ioctl_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8181f57f)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff818a9c1f)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff819f416f)
Location: drivers/dma-buf/sync_file.c:314
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81b714df)
Location: drivers/dma-buf/sync_file.c:207
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81bc4d21)
Location: drivers/dma-buf/sync_file.c:207
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81c19606)
Location: drivers/dma-buf/sync_file.c:207
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffff80001096ab98)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c0a409b8)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c000000000a233fc)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffe0005d6004)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8171dbaf)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816f700f)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8175c97f)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8177801f)
Location: drivers/dma-buf/sync_file.c:323
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
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
</ul>
