# Function: <code>__mmu_interval_notifier_insert</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d1c90)
Location: mm/mmu_notifier.c:897
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff812d1c90-ffffffff812d1d7c: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812dd690)
Location: mm/mmu_notifier.c:913
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff812dd690-ffffffff812dd788: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e4e10)
Location: mm/mmu_notifier.c:913
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff812e4e10-ffffffff812e4f08: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132cc20)
Location: mm/mmu_notifier.c:913
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff8132cc20-ffffffff8132cd18: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139cb10)
Location: mm/mmu_notifier.c:913
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff8139cb10-ffffffff8139cc32: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141bf10)
Location: mm/mmu_notifier.c:913
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff8141bf10-ffffffff8141c032: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8144f4c0)
Location: mm/mmu_notifier.c:913
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff8144f4c0-ffffffff8144f5e4: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, struct mmu_notifier_subscriptions *subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff814891a0)
Location: mm/mmu_notifier.c:905
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
**Symbols:**

```
ffffffff814891a0-ffffffff814892c4: __mmu_interval_notifier_insert (STB_LOCAL)
```
</details>
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
