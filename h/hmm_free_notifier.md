# Function: <code>hmm_free_notifier</code>

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
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d4d90)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffffffff812d4d90-ffffffff812d4dd2: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037a280)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffff80001037a280-ffff80001037a2f8: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c056548c)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
c056548c-c0565514: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046e830)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
c00000000046e830-c00000000046e894: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe000251538)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffffffe000251538-ffffffe000251598: hmm_free_notifier (STB_LOCAL)
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
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cd370)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffffffff812cd370-ffffffff812cd3b2: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be1e0)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffffffff812be1e0-ffffffff812be222: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb180)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffffffff812cb180-ffffffff812cb1c2: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hmm_free_notifier(struct mmu_notifier *mn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dbee0)
Location: mm/hmm.c:46
Inline: False
```
**Symbols:**

```
ffffffff812dbee0-ffffffff812dbf22: hmm_free_notifier (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
