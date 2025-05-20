# Function: <code>apply_workqueue_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c7c0)
Location: kernel/workqueue.c:3653
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff8109c7c0-ffffffff8109c808: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f9b0)
Location: kernel/workqueue.c:3751
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff8109f9b0-ffffffff8109f9f8: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4880)
Location: kernel/workqueue.c:3779
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a4880-ffffffff810a48c8: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a19e0)
Location: kernel/workqueue.c:3788
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a19e0-ffffffff810a1a28: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8240)
Location: kernel/workqueue.c:3799
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a8240-ffffffff810a8288: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aea50)
Location: kernel/workqueue.c:3871
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810aea50-ffffffff810aea98: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b7bb0)
Location: kernel/workqueue.c:3894
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810b7bb0-ffffffff810b7bf8: apply_workqueue_attrs (STB_GLOBAL)
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
In kernel/workqueue.c (ffffffff810beba9)
Location: kernel/workqueue.c:4035
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3fc0)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c3fc0-ffffffff810c4007: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cb68d)
Location: kernel/workqueue.c:4055
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
Direct callers:
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff810cbc40-ffffffff810cbc87: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c67bd)
Location: kernel/workqueue.c:4068
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff810c6d70-ffffffff810c6db7: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c80fd)
Location: kernel/workqueue.c:4075
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffff810c8510-ffffffff810c8557: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810dc5a2)
Location: kernel/workqueue.c:4114
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
Direct callers:
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffff810db0b0-ffffffff810db0f7: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f5d36)
Location: kernel/workqueue.c:4097
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff810f48b0-ffffffff810f48fb: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81118281)
Location: kernel/workqueue.c:4106
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81116c30-ffffffff81116c7b: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81125490)
Location: kernel/workqueue.c:4434
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81123bb0-ffffffff81123bfb: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112d7b4)
Location: kernel/workqueue.c:4462
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8112e230-ffffffff8112e27b: apply_workqueue_attrs (STB_GLOBAL)
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
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121da0)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffff800010121da0-ffff800010121e04: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375788)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
c0375788-c03757d8: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016b6c0)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
c00000000016b6c0-c00000000016b740: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000da99c)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffe0000da99c-ffffffe0000da9f2: apply_workqueue_attrs (STB_GLOBAL)
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
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be330)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810be330-ffffffff810be377: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810acb60)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810acb60-ffffffff810acba7: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd890)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810bd890-ffffffff810bd8d7: apply_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apply_workqueue_attrs(struct workqueue_struct *wq, const struct workqueue_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5c10)
Location: kernel/workqueue.c:4046
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
```
**Symbols:**

```
ffffffff810c5c10-ffffffff810c5c57: apply_workqueue_attrs (STB_GLOBAL)
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
