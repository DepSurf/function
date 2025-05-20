# Function: <code>irq_set_affinity_hint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dc200)
Location: kernel/irq/manage.c:251
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
**Symbols:**

```
ffffffff810dc200-ffffffff810dc290: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1910)
Location: kernel/irq/manage.c:264
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
**Symbols:**

```
ffffffff810e1910-ffffffff810e19a0: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8260)
Location: kernel/irq/manage.c:264
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
**Symbols:**

```
ffffffff810e8260-ffffffff810e82f0: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7680)
Location: kernel/irq/manage.c:238
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff810e7680-ffffffff810e7710: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810efa00)
Location: kernel/irq/manage.c:255
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff810efa00-ffffffff810efa90: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7e30)
Location: kernel/irq/manage.c:288
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff810f7e30-ffffffff810f7ec0: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81103580)
Location: kernel/irq/manage.c:288
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff81103580-ffffffff81103610: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110bf90)
Location: kernel/irq/manage.c:315
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff8110bf90-ffffffff8110c022: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811183c0)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811183c0-ffffffff81118452: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81123c20)
Location: kernel/irq/manage.c:395
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff81123c20-ffffffff81123cdf: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fa70)
Location: kernel/irq/manage.c:465
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff8111fa70-ffffffff8111fb2f: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fd20)
Location: kernel/irq/manage.c:465
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff8111fd20-ffffffff8111fddf: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811401c0)
Location: kernel/irq/manage.c:489
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811401c0-ffffffff8114027f: irq_set_affinity_hint (STB_GLOBAL)
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
In drivers/virtio/virtio_pci_common.c (ffffffff818c42ad)
Location: include/linux/interrupt.h:349
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81a1499d)
Location: include/linux/interrupt.h:349
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81a5da0d)
Location: include/linux/interrupt.h:349
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017ac20)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_offline_cpu
```
**Symbols:**

```
ffff80001017ac20-ffff80001017acc0: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cbe2c)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_offline_cpu
```
**Symbols:**

```
c03cbe2c-c03cbed4: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d5160)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
c0000000001d5160-c0000000001d522c: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe00011497c)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffe00011497c-ffffffe0001149e2: irq_set_affinity_hint (STB_GLOBAL)
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
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811109a0)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811109a0-ffffffff81110a32: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811016d0)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811016d0-ffffffff81101762: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e890)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff8110e890-ffffffff8110e922: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_affinity_hint(unsigned int irq, const struct cpumask *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119dc0)
Location: kernel/irq/manage.c:319
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff81119dc0-ffffffff81119e52: irq_set_affinity_hint (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
