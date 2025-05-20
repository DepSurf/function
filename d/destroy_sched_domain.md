# Function: <code>destroy_sched_domain</code>

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
In kernel/sched/core.c (ffffffff810a8336)
Location: kernel/sched/core.c:5968
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
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
In kernel/sched/core.c (ffffffff810aaee5)
Location: kernel/sched/core.c:5929
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0760)
Location: kernel/sched/core.c:5950
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810b0760-ffffffff810b07fe: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cb160)
Location: kernel/sched/topology.c:345
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810cb160-ffffffff810cb1fe: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d2950)
Location: kernel/sched/topology.c:363
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810d2950-ffffffff810d29a3: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810daa40)
Location: kernel/sched/topology.c:355
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810daa40-ffffffff810daa93: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e4590)
Location: kernel/sched/topology.c:549
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810e4590-ffffffff810e45e3: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eb1c0)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810eb1c0-ffffffff810eb218: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f6b60)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810f6b60-ffffffff810f6bb8: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811008f0)
Location: kernel/sched/topology.c:576
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff811008f0-ffffffff8110094c: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ff440)
Location: kernel/sched/topology.c:604
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810ff440-ffffffff810ff49c: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101510)
Location: kernel/sched/topology.c:604
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff81101510-ffffffff8110156c: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111d730)
Location: kernel/sched/topology.c:604
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff8111d730-ffffffff8111d78c: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113e7e0)
Location: kernel/sched/topology.c:624
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff8113e7e0-ffffffff8113e84d: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168d70)
Location: kernel/sched/topology.c:624
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff81168d70-ffffffff81168ddd: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811794e0)
Location: kernel/sched/topology.c:626
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff811794e0-ffffffff8117954d: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187020)
Location: kernel/sched/topology.c:628
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff81187020-ffffffff8118708d: destroy_sched_domain (STB_LOCAL)
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
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015ad58)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffff80001015ad58-ffff80001015ade0: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a77a4)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
c03a77a4-c03a781c: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001af000)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
c0000000001af000-c0000000001af0bc: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000100436)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffe000100436-ffffffe0001004a2: destroy_sched_domain (STB_LOCAL)
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
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eff60)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810eff60-ffffffff810effb8: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dffd0)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810dffd0-ffffffff810e0028: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ed090)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810ed090-ffffffff810ed0e8: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f80d0)
Location: kernel/sched/topology.c:578
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:destroy_sched_domains_rcu
```
**Symbols:**

```
ffffffff810f80d0-ffffffff810f8128: destroy_sched_domain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
