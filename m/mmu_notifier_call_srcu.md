# Function: <code>mmu_notifier_call_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3950)
Location: mm/mmu_notifier.c:30
Inline: False
```
**Symbols:**

```
ffffffff811e3950-ffffffff811e396d: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812023d0)
Location: mm/mmu_notifier.c:30
Inline: False
```
**Symbols:**

```
ffffffff812023d0-ffffffff812023ed: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81214210)
Location: mm/mmu_notifier.c:30
Inline: False
```
**Symbols:**

```
ffffffff81214210-ffffffff8121422d: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121f6a0)
Location: mm/mmu_notifier.c:31
Inline: False
```
**Symbols:**

```
ffffffff8121f6a0-ffffffff8121f6bd: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123a8a0)
Location: mm/mmu_notifier.c:31
Inline: False
```
**Symbols:**

```
ffffffff8123a8a0-ffffffff8123a8bd: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125de00)
Location: mm/mmu_notifier.c:31
Inline: False
```
**Symbols:**

```
ffffffff8125de00-ffffffff8125de1d: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81272690)
Location: mm/mmu_notifier.c:31
Inline: False
```
**Symbols:**

```
ffffffff81272690-ffffffff812726ad: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmu_notifier_call_srcu(struct callback_head *rcu, void (*func)(struct callback_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128de00)
Location: mm/mmu_notifier.c:29
Inline: False
Direct callers:
  - mm/hmm.c:hmm_free
```
**Symbols:**

```
ffffffff8128de00-ffffffff8128de1d: mmu_notifier_call_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
