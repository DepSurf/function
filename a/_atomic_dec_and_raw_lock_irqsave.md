# Function: <code>_atomic_dec_and_raw_lock_irqsave</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _atomic_dec_and_raw_lock_irqsave(atomic_t *atomic, raw_spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8201fc50)
Location: lib/dec_and_lock.c:68
Inline: False
Direct callers:
  - kernel/events/core.c:put_pmu_ctx
```
**Symbols:**

```
ffffffff8201fc50-ffffffff8201fcb6: _atomic_dec_and_raw_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _atomic_dec_and_raw_lock_irqsave(atomic_t *atomic, raw_spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8209fb60)
Location: lib/dec_and_lock.c:68
Inline: False
Direct callers:
  - kernel/events/core.c:put_pmu_ctx
```
**Symbols:**

```
ffffffff8209fb60-ffffffff8209fbc4: _atomic_dec_and_raw_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _atomic_dec_and_raw_lock_irqsave(atomic_t *atomic, raw_spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff82177b30)
Location: lib/dec_and_lock.c:68
Inline: False
Direct callers:
  - kernel/events/core.c:put_pmu_ctx
```
**Symbols:**

```
ffffffff82177b30-ffffffff82177b94: _atomic_dec_and_raw_lock_irqsave (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
