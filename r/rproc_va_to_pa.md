# Function: <code>rproc_va_to_pa</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f36e0)
Location: drivers/remoteproc/remoteproc_core.c:144
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff818f36e0-ffffffff818f3762: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9250)
Location: drivers/remoteproc/remoteproc_core.c:147
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff819c9250-ffffffff819c92c3: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8ea0)
Location: drivers/remoteproc/remoteproc_core.c:146
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff819c8ea0-ffffffff819c8f13: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819adf70)
Location: drivers/remoteproc/remoteproc_core.c:146
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff819adf70-ffffffff819adfe3: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c430)
Location: drivers/remoteproc/remoteproc_core.c:147
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81a5c430-ffffffff81a5c4a3: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc440)
Location: drivers/remoteproc/remoteproc_core.c:147
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81bcc440-ffffffff81bcc4bf: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76580)
Location: drivers/remoteproc/remoteproc_core.c:146
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81d76580-ffffffff81d765ff: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de44c0)
Location: drivers/remoteproc/remoteproc_core.c:146
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81de44c0-ffffffff81de453f: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a5b0)
Location: drivers/remoteproc/remoteproc_core.c:146
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81e9a5b0-ffffffff81e9a62f: rproc_va_to_pa (STB_GLOBAL)
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
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f398)
Location: drivers/remoteproc/remoteproc_core.c:144
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffff800010b7f398-ffff800010b7f478: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c62b00)
Location: drivers/remoteproc/remoteproc_core.c:144
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
c0c62b00-c0c62be8: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b540)
Location: drivers/remoteproc/remoteproc_core.c:144
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
c000000000c5b540-c000000000c5b670: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894a10)
Location: drivers/remoteproc/remoteproc_core.c:144
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81894a10-ffffffff81894a92: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t rproc_va_to_pa(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905170)
Location: drivers/remoteproc/remoteproc_core.c:144
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffffffff81905170-ffffffff819051f2: rproc_va_to_pa (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
