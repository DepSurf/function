# Function: <code>irq_set_percpu_devid_partition</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df900)
Location: kernel/irq/irqdesc.c:629
Inline: True
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff810df900-ffffffff810df996: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e61e0)
Location: kernel/irq/irqdesc.c:817
Inline: True
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff810e61e0-ffffffff810e6276: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5830)
Location: kernel/irq/irqdesc.c:834
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff810e5830-ffffffff810e58c6: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810edb00)
Location: kernel/irq/irqdesc.c:823
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff810edb00-ffffffff810edb96: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f5f40)
Location: kernel/irq/irqdesc.c:840
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff810f5f40-ffffffff810f5fd6: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811016d0)
Location: kernel/irq/irqdesc.c:845
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff811016d0-ffffffff81101766: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109ed0)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff81109ed0-ffffffff81109f61: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811162a0)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff811162a0-ffffffff81116331: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121f50)
Location: kernel/irq/irqdesc.c:907
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff81121f50-ffffffff81121fe1: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111dfd0)
Location: kernel/irq/irqdesc.c:858
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff8111dfd0-ffffffff8111e061: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e270)
Location: kernel/irq/irqdesc.c:858
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff8111e270-ffffffff8111e301: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e6f0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff8113e6f0-ffffffff8113e781: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161ca0)
Location: kernel/irq/irqdesc.c:847
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff81161ca0-ffffffff81161d3b: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195490)
Location: kernel/irq/irqdesc.c:874
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff81195490-ffffffff8119552b: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6e60)
Location: kernel/irq/irqdesc.c:893
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff811a6e60-ffffffff811a6efb: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6980)
Location: kernel/irq/irqdesc.c:893
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff811b6980-ffffffff811b6a52: irq_set_percpu_devid_partition (STB_GLOBAL)
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177ee0)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
```
**Symbols:**

```
ffff800010177ee0-ffff800010177f88: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9820)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
```
**Symbols:**

```
c03c9820-c03c98c4: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d1950)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
c0000000001d1950-c0000000001d1a40: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000112ab6)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffe000112ab6-ffffffe000112b4c: irq_set_percpu_devid_partition (STB_GLOBAL)
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e880)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff8110e880-ffffffff8110e911: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff5d0)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff810ff5d0-ffffffff810ff661: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c770)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff8110c770-ffffffff8110c801: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117c80)
Location: kernel/irq/irqdesc.c:900
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
**Symbols:**

```
ffffffff81117c80-ffffffff81117d11: irq_set_percpu_devid_partition (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
