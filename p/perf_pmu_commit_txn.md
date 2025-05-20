# Function: <code>perf_pmu_commit_txn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117aa20)
Location: kernel/events/core.c:7430
Inline: True
```
**Symbols:**

```
ffffffff8117aa20-ffffffff8117aa5e: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118b700)
Location: kernel/events/core.c:8422
Inline: True
```
**Symbols:**

```
ffffffff8118b700-ffffffff8118b723: perf_pmu_commit_txn.part.99 (STB_LOCAL)
ffffffff8118b760-ffffffff8118b787: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8119a5a0)
Location: kernel/events/core.c:8611
Inline: True
```
**Symbols:**

```
ffffffff8119a5a0-ffffffff8119a5c3: perf_pmu_commit_txn.part.99 (STB_LOCAL)
ffffffff8119a600-ffffffff8119a627: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2f80)
Location: kernel/events/core.c:8849
Inline: True
```
**Symbols:**

```
ffffffff811a2f80-ffffffff811a2fb6: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7160)
Location: kernel/events/core.c:8857
Inline: True
```
**Symbols:**

```
ffffffff811b7160-ffffffff811b7199: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d5da0)
Location: kernel/events/core.c:9379
Inline: True
```
**Symbols:**

```
ffffffff811d5d50-ffffffff811d5d6c: perf_pmu_commit_txn.part.110 (STB_LOCAL)
ffffffff811d5da0-ffffffff811d5dc4: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e6440)
Location: kernel/events/core.c:9424
Inline: True
```
**Symbols:**

```
ffffffff811e63f0-ffffffff811e640c: perf_pmu_commit_txn.part.110 (STB_LOCAL)
ffffffff811e6440-ffffffff811e6464: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdc40)
Location: kernel/events/core.c:9727
Inline: True
```
**Symbols:**

```
ffffffff811fdc40-ffffffff811fdc78: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120aef0)
Location: kernel/events/core.c:9843
Inline: True
```
**Symbols:**

```
ffffffff8120aef0-ffffffff8120af28: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81235800)
Location: kernel/events/core.c:10391
Inline: False
```
**Symbols:**

```
ffffffff81235800-ffffffff8123583c: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f9d0)
Location: kernel/events/core.c:10673
Inline: False
```
**Symbols:**

```
ffffffff8123f9d0-ffffffff8123fa0c: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243b70)
Location: kernel/events/core.c:10803
Inline: False
```
**Symbols:**

```
ffffffff81243b70-ffffffff81243bac: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127e4c0)
Location: kernel/events/core.c:10915
Inline: False
```
**Symbols:**

```
ffffffff8127e4c0-ffffffff8127e4fc: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d2960)
Location: kernel/events/core.c:10851
Inline: False
```
**Symbols:**

```
ffffffff812d2960-ffffffff812d29b5: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b220)
Location: kernel/events/core.c:11217
Inline: False
```
**Symbols:**

```
ffffffff8133b220-ffffffff8133b275: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c4e0)
Location: kernel/events/core.c:11259
Inline: False
```
**Symbols:**

```
ffffffff8136c4e0-ffffffff8136c535: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395710)
Location: kernel/events/core.c:11329
Inline: False
```
**Symbols:**

```
ffffffff81395710-ffffffff81395765: perf_pmu_commit_txn (STB_LOCAL)
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
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010299e88)
Location: kernel/events/core.c:9843
Inline: False
```
**Symbols:**

```
ffff800010299e88-ffff800010299ec0: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c94b0)
Location: kernel/events/core.c:9843
Inline: False
```
**Symbols:**

```
c04c94b0-c04c94e8: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000349830)
Location: kernel/events/core.c:9843
Inline: False
```
**Symbols:**

```
c000000000349830-c000000000349894: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cc9c0)
Location: kernel/events/core.c:9843
Inline: False
```
**Symbols:**

```
ffffffe0001cc9c0-ffffffe0001cca08: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203510)
Location: kernel/events/core.c:9843
Inline: True
```
**Symbols:**

```
ffffffff81203510-ffffffff81203548: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6260)
Location: kernel/events/core.c:9843
Inline: True
```
**Symbols:**

```
ffffffff811f6260-ffffffff811f6298: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812012e0)
Location: kernel/events/core.c:9843
Inline: True
```
**Symbols:**

```
ffffffff812012e0-ffffffff81201318: perf_pmu_commit_txn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int perf_pmu_commit_txn(struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210660)
Location: kernel/events/core.c:9843
Inline: True
```
**Symbols:**

```
ffffffff81210660-ffffffff81210698: perf_pmu_commit_txn (STB_LOCAL)
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
