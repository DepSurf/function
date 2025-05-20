# Function: <code>sk_storage_lookup</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81953415)
Location: net/core/bpf_sk_storage.c:297
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (ffffffff819897c5)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a611a3)
Location: net/core/bpf_sk_storage.c:300
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/bpf_sk_storage.c (ffff800010c32014)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (c0d48ab0)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (c000000000d2afc8)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (ffffffe0007a77de)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (ffffffff81929635)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (ffffffff818e33e5)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (ffffffff8197a7c5)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
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
In net/core/bpf_sk_storage.c (ffffffff8199ccf5)
Location: net/core/bpf_sk_storage.c:299
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
</details>
</li>
</ul>

## Differences
