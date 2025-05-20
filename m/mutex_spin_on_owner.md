# Function: <code>mutex_spin_on_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810c9a80)
Location: kernel/locking/mutex.c:225
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
**Symbols:**

```
ffffffff810c9a80-ffffffff810c9acd: mutex_spin_on_owner.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ce3f0)
Location: kernel/locking/mutex.c:225
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
**Symbols:**

```
ffffffff810ce3f0-ffffffff810ce43d: mutex_spin_on_owner.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810d5050)
Location: kernel/locking/mutex.c:353
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
**Symbols:**

```
ffffffff810d5050-ffffffff810d50be: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810d4190)
Location: kernel/locking/mutex.c:424
Inline: False
```
**Symbols:**

```
ffffffff810d4190-ffffffff810d422c: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810dc0e0)
Location: kernel/locking/mutex.c:424
Inline: False
```
**Symbols:**

```
ffffffff810dc0e0-ffffffff810dc182: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810e4720)
Location: kernel/locking/mutex.c:425
Inline: False
```
**Symbols:**

```
ffffffff810e4720-ffffffff810e47c4: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810efd10)
Location: kernel/locking/mutex.c:523
Inline: False
```
**Symbols:**

```
ffffffff810efd10-ffffffff810efdb4: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f7770)
Location: kernel/locking/mutex.c:524
Inline: False
```
**Symbols:**

```
ffffffff810f7770-ffffffff810f780e: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81103530)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff81103530-ffffffff811035ce: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110e050)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff8110e050-ffffffff8110e0ef: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110b310)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff8110b310-ffffffff8110b3ae: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110d1a0)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff8110d1a0-ffffffff8110d23e: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8112c9e0)
Location: kernel/locking/mutex.c:346
Inline: False
```
**Symbols:**

```
ffffffff8112c9e0-ffffffff8112ca7e: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8114d980)
Location: kernel/locking/mutex.c:352
Inline: False
```
**Symbols:**

```
ffffffff8114d980-ffffffff8114da61: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8117cc50)
Location: kernel/locking/mutex.c:352
Inline: False
```
**Symbols:**

```
ffffffff8117cc50-ffffffff8117cd38: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8118d7f0)
Location: kernel/locking/mutex.c:352
Inline: False
```
**Symbols:**

```
ffffffff8118d7f0-ffffffff8118d8d8: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8119c1a0)
Location: kernel/locking/mutex.c:352
Inline: False
```
**Symbols:**

```
ffffffff8119c1a0-ffffffff8119c288: mutex_spin_on_owner (STB_LOCAL)
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
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010168628)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffff800010168628-ffff8000101686d4: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4d18)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
c03b4d18-c03b4df4: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c0460)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
c0000000001c0460-c0000000001c054c: mutex_spin_on_owner (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc840)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff810fc840-ffffffff810fc8de: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810eca50)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff810eca50-ffffffff810ecaee: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9a00)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff810f9a00-ffffffff810f9a9e: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mutex_spin_on_owner(struct mutex *lock, struct task_struct *owner, struct ww_acquire_ctx *ww_ctx, struct mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104b60)
Location: kernel/locking/mutex.c:550
Inline: False
```
**Symbols:**

```
ffffffff81104b60-ffffffff81104c09: mutex_spin_on_owner (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ww_acquire_ctx *ww_ctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct mutex_waiter *waiter</code>
</li>
</ul>
</details>
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
