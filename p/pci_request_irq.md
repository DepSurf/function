# Function: <code>pci_request_irq</code>

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
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff814b5550)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff814b5550-ffffffff814b561c: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff814f4f50)
Location: drivers/pci/irq.c:84
Inline: False
```
**Symbols:**

```
ffffffff814f4f50-ffffffff814f501c: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff81524fe0)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff81524fe0-ffffffff815250a5: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8153ae60)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff8153ae60-ffffffff8153af3a: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8156a880)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff8156a880-ffffffff8156a95d: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8158b850)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff8158b850-ffffffff8158b92d: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff816328f0)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff816328f0-ffffffff816329cd: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff81657b20)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff81657b20-ffffffff81657bfd: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8163a3f0)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff8163a3f0-ffffffff8163a4c4: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff816aac10)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff816aac10-ffffffff816aace4: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff817cdb80)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff817cdb80-ffffffff817cdc73: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff818ed4b0)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff818ed4b0-ffffffff818ed5ae: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff819309b0)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff819309b0-ffffffff81930aae: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff819793e0)
Location: drivers/pci/irq.c:33
Inline: False
```
**Symbols:**

```
ffffffff819793e0-ffffffff819794de: pci_request_irq (STB_GLOBAL)
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
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffff8000106f05e8)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffff8000106f05e8-ffff8000106f06ec: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (c088b118)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
c088b118-c088b1d8: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (c00000000086dc50)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
c00000000086dc50-c00000000086dd6c: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffe0004c417a)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffe0004c417a-ffffffe0004c421c: pci_request_irq (STB_GLOBAL)
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
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8157f6d0)
Location: drivers/pci/irq.c:83
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:queue_request_irq
  - drivers/nvme/host/pci.c:queue_request_irq
```
**Symbols:**

```
ffffffff8157f6d0-ffffffff8157f7ad: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8156e4b0)
Location: drivers/pci/irq.c:83
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:queue_request_irq
  - drivers/nvme/host/pci.c:queue_request_irq
```
**Symbols:**

```
ffffffff8156e4b0-ffffffff8156e58d: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff8157f5a0)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff8157f5a0-ffffffff8157f67d: pci_request_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_request_irq(struct pci_dev *dev, unsigned int nr, irq_handler_t handler, irq_handler_t thread_fn, void *dev_id, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/irq.c (ffffffff81599a50)
Location: drivers/pci/irq.c:83
Inline: False
```
**Symbols:**

```
ffffffff81599a50-ffffffff81599b2d: pci_request_irq (STB_GLOBAL)
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
