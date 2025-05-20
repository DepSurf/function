# Function: <code>kfence_guarded_free</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfence_guarded_free(void *addr, struct kfence_metadata *meta, bool zombie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8133c230)
Location: mm/kfence/core.c:355
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_shutdown_cache
  - mm/kfence/core.c:rcu_guarded_free
```
**Symbols:**

```
ffffffff8133c230-ffffffff8133c569: kfence_guarded_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfence_guarded_free(void *addr, struct kfence_metadata *meta, bool zombie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813af380)
Location: mm/kfence/core.c:459
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_shutdown_cache
  - mm/kfence/core.c:rcu_guarded_free
```
**Symbols:**

```
ffffffff813af380-ffffffff813af7bc: kfence_guarded_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfence_guarded_free(void *addr, struct kfence_metadata *meta, bool zombie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8142f910)
Location: mm/kfence/core.c:458
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_shutdown_cache
  - mm/kfence/core.c:rcu_guarded_free
```
**Symbols:**

```
ffffffff8142f910-ffffffff8142fd4c: kfence_guarded_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfence_guarded_free(void *addr, struct kfence_metadata *meta, bool zombie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff814654b0)
Location: mm/kfence/core.c:486
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_shutdown_cache
  - mm/kfence/core.c:rcu_guarded_free
```
**Symbols:**

```
ffffffff814654b0-ffffffff814656d5: kfence_guarded_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfence_guarded_free(void *addr, struct kfence_metadata *meta, bool zombie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81494750)
Location: mm/kfence/core.c:490
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_shutdown_cache
  - mm/kfence/core.c:rcu_guarded_free
```
**Symbols:**

```
ffffffff81494750-ffffffff814949c5: kfence_guarded_free (STB_LOCAL)
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
