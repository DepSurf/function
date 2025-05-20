# Function: <code>cpufreq_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b1820)
Location: drivers/cpufreq/cpufreq.c:1122
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_callback
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff816b1820-ffffffff816b203f: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81713990)
Location: drivers/cpufreq/cpufreq.c:1172
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_callback
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81713990-ffffffff817141c7: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81745780)
Location: drivers/cpufreq/cpufreq.c:1129
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81745780-ffffffff81745f36: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81763ea0)
Location: drivers/cpufreq/cpufreq.c:1143
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81763ea0-ffffffff817645e1: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9e90)
Location: drivers/cpufreq/cpufreq.c:1175
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff817d9e90-ffffffff817da5cd: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1168
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff818229a0-ffffffff81823007: cpufreq_online (STB_LOCAL)
ffffffff8182328b-ffffffff81823348: cpufreq_online.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1173
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff8184e880-ffffffff8184eecf: cpufreq_online (STB_LOCAL)
ffffffff8184f14b-ffffffff8184f208: cpufreq_online.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1280
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81891a90-ffffffff8189228d: cpufreq_online (STB_LOCAL)
ffffffff818925cd-ffffffff81892725: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff818c3ab0-ffffffff818c43a0: cpufreq_online (STB_LOCAL)
ffffffff818c4659-ffffffff818c4760: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1315
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81996030-ffffffff8199655a: cpufreq_online (STB_LOCAL)
ffffffff819968ab-ffffffff81996932: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1319
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81999140-ffffffff81999684: cpufreq_online (STB_LOCAL)
ffffffff81c298df-ffffffff81c2993d: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1316
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff8197d9a0-ffffffff8197e1be: cpufreq_online (STB_LOCAL)
ffffffff81c1bc7b-ffffffff81c1bcdb: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1316
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81a26a30-ffffffff81a272e4: cpufreq_online (STB_LOCAL)
ffffffff81d2c0e0-ffffffff81d2c142: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1322
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81b90ab0-ffffffff81b9137b: cpufreq_online (STB_LOCAL)
ffffffff81ef839d-ffffffff81ef83fc: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d30d00)
Location: drivers/cpufreq/cpufreq.c:1320
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81d30d00-ffffffff81d31647: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1327
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81d99f80-ffffffff81d9aa01: cpufreq_online (STB_LOCAL)
ffffffff8212a07b-ffffffff8212a0fc: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1368
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81e51c30-ffffffff81e52773: cpufreq_online (STB_LOCAL)
ffffffff8220be55-ffffffff8220bed6: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b21510)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
```
In drivers/cpufreq/cpufreq-dt.c (ffff800010b25ed0)
Location: drivers/cpufreq/cpufreq-dt.c:297
Inline: True
```
**Symbols:**

```
ffff800010b21510-ffff800010b21f08: cpufreq_online (STB_LOCAL)
ffff800010b25ed0-ffff800010b25eec: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfbbb0)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
```
In drivers/cpufreq/cpufreq-dt.c (c0bffd5c)
Location: drivers/cpufreq/cpufreq-dt.c:297
Inline: True
```
**Symbols:**

```
c0bfbbb0-c0bfc588: cpufreq_online (STB_LOCAL)
c0bffd5c-c0bffd78: cpufreq_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c15400)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
c000000000c15400-c000000000c160d8: cpufreq_online (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff818681d0-ffffffff81868ac0: cpufreq_online (STB_LOCAL)
ffffffff81868d79-ffffffff81868e80: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff81830e80-ffffffff81831770: cpufreq_online (STB_LOCAL)
ffffffff81831a29-ffffffff81831b30: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff818b8f60-ffffffff818b9850: cpufreq_online (STB_LOCAL)
ffffffff818b9b09-ffffffff818b9c10: cpufreq_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cpufreq_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1298
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff818d5240-ffffffff818d5b30: cpufreq_online (STB_LOCAL)
ffffffff818d5de9-ffffffff818d5ef0: cpufreq_online.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
