# Function: <code>__padata_set_cpumasks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __padata_set_cpumasks(struct padata_instance *pinst, struct cpumask *pcpumask, struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8118a480)
Location: kernel/padata.c:576
Inline: False
Direct callers:
  - kernel/padata.c:padata_set_cpumasks
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8118a480-ffffffff8118a56e: __padata_set_cpumasks (STB_LOCAL)
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
In kernel/padata.c (ffffffff8119cba2)
Location: kernel/padata.c:576
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff811ac5ca)
Location: kernel/padata.c:573
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff811b3c0a)
Location: kernel/padata.c:569
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff811c789a)
Location: kernel/padata.c:634
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff811e7ae9)
Location: kernel/padata.c:635
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff811f8a39)
Location: kernel/padata.c:635
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff812104e6)
Location: kernel/padata.c:647
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff8121dc40)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __padata_set_cpumasks(struct padata_instance *pinst, cpumask_var_t pcpumask, cpumask_var_t cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81249d50)
Location: kernel/padata.c:722
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81249d50-ffffffff81249e6d: __padata_set_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __padata_set_cpumasks(struct padata_instance *pinst, cpumask_var_t pcpumask, cpumask_var_t cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81254060)
Location: kernel/padata.c:691
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81254060-ffffffff8125417d: __padata_set_cpumasks (STB_LOCAL)
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
In kernel/padata.c (ffffffff81258693)
Location: kernel/padata.c:691
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff812942b3)
Location: kernel/padata.c:678
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff812ea603)
Location: kernel/padata.c:678
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff813544e3)
Location: kernel/padata.c:691
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff813856e4)
Location: kernel/padata.c:691
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff813aeb74)
Location: kernel/padata.c:691
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffff8000102a9434)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (c04d8740)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (c00000000035d85c)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffe0001d2648)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff81216290)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff81208ff0)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff81214030)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff81223270)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
