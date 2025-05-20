# Function: <code>vfio_pci_set_ctx_trigger_single</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8cd0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:545
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff817d8cd0-ffffffff817d8d94: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a65c0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:559
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff818a65c0-ffffffff818a6687: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b54b0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:561
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff818b54b0-ffffffff818b5577: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898950)
Location: drivers/vfio/pci/vfio_pci_intrs.c:561
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff81898950-ffffffff81898a17: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c360)
Location: drivers/vfio/pci/vfio_pci_intrs.c:561
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff8192c360-ffffffff8192c427: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82150)
Location: drivers/vfio/pci/vfio_pci_intrs.c:561
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff81a82150-ffffffff81a821fc: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8950)
Location: drivers/vfio/pci/vfio_pci_intrs.c:545
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
c000000000ab8950-c000000000ab8b30: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782d80)
Location: drivers/vfio/pci/vfio_pci_intrs.c:545
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff81782d80-ffffffff81782e44: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdb50)
Location: drivers/vfio/pci/vfio_pci_intrs.c:545
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff817cdb50-ffffffff817cdc14: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_ctx_trigger_single(struct eventfd_ctx **ctx, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7df0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:545
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_req_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_err_trigger
```
**Symbols:**

```
ffffffff817e7df0-ffffffff817e7eb4: vfio_pci_set_ctx_trigger_single (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
