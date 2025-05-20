# Function: <code>perform_atomic_semop_slow</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81372050)
Location: ipc/sem.c:584
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813853ce)
Location: ipc/sem.c:595
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813a9c4e)
Location: ipc/sem.c:598
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:630
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:629
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
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
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148a2f0)
Location: ipc/sem.c:644
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff8148a2f0-ffffffff8148a4cb: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a78a0)
Location: ipc/sem.c:643
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff814a78a0-ffffffff814a7a7b: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814ad7e0)
Location: ipc/sem.c:643
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff814ad7e0-ffffffff814ad9bb: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81505cc0)
Location: ipc/sem.c:646
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff81505cc0-ffffffff81505e9b: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81597b50)
Location: ipc/sem.c:646
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff81597b50-ffffffff81597d35: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81640d30)
Location: ipc/sem.c:646
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff81640d30-ffffffff81640f15: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perform_atomic_semop_slow(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816792c0)
Location: ipc/sem.c:646
Inline: False
Direct callers:
  - ipc/sem.c:perform_atomic_semop
```
**Symbols:**

```
ffffffff816792c0-ffffffff816794a5: perform_atomic_semop_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b5903)
Location: ipc/sem.c:646
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dca08)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe00038721a)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:625
Inline: True
Inline callers:
  - ipc/sem.c:perform_atomic_semop
```
</details>
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
</ul>
