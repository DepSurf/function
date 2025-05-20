# Function: <code>shmem_read_mapping_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811874a1)
Location: include/linux/shmem_fs.h:63
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81199a91)
Location: include/linux/shmem_fs.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
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
In kernel/events/uprobes.c (ffffffff811a91f1)
Location: include/linux/shmem_fs.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
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
In kernel/events/uprobes.c (ffffffff811b0e82)
Location: include/linux/shmem_fs.h:94
Inline: True
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
In kernel/events/uprobes.c (ffffffff811c4a1b)
Location: include/linux/shmem_fs.h:97
Inline: True
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
In kernel/events/uprobes.c (ffffffff811e4f4e)
Location: include/linux/shmem_fs.h:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f5560)
Location: include/linux/shmem_fs.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170b177)
Location: include/linux/shmem_fs.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120d2a4)
Location: include/linux/shmem_fs.h:99
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817467a9)
Location: include/linux/shmem_fs.h:99
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121a634)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a8f9)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81246207)
Location: include/linux/shmem_fs.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_insn
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182ca83)
Location: include/linux/shmem_fs.h:102
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81250877)
Location: include/linux/shmem_fs.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_insn
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183dbb4)
Location: include/linux/shmem_fs.h:106
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81255d8e)
Location: include/linux/shmem_fs.h:106
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820d44)
Location: include/linux/shmem_fs.h:106
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291a41)
Location: include/linux/shmem_fs.h:111
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab685)
Location: include/linux/shmem_fs.h:111
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e71a3)
Location: include/linux/shmem_fs.h:111
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5e18)
Location: include/linux/shmem_fs.h:111
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81350ca3)
Location: include/linux/shmem_fs.h:119
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b733e2)
Location: include/linux/shmem_fs.h:119
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81381f02)
Location: include/linux/shmem_fs.h:130
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d2a)
Location: include/linux/shmem_fs.h:130
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813ab2e2)
Location: include/linux/shmem_fs.h:150
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b899)
Location: include/linux/shmem_fs.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a624c)
Location: include/linux/shmem_fs.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cbc0)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5464)
Location: include/linux/shmem_fs.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (c0a420d8)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000358940)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25398)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In drivers/dma-buf/udmabuf.c (ffffffe0005d73ec)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81212c84)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171efe9)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812059f4)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8419)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81210a24)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175ddb9)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121f934)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779419)
Location: include/linux/shmem_fs.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
</ul>

## Differences
