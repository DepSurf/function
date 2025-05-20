# Function: <code>set_work_pool_and_clear_pending</code>

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
In kernel/workqueue.c (ffffffff810989d0)
Location: kernel/workqueue.c:641
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff8109bf8e)
Location: kernel/workqueue.c:632
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0fd2)
Location: kernel/workqueue.c:634
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff8109e53b)
Location: kernel/workqueue.c:634
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct *work, int pool_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3230)
Location: kernel/workqueue.c:636
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:process_one_work
```
**Symbols:**

```
ffffffff810a3230-ffffffff810a3256: set_work_pool_and_clear_pending (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810ac5d3)
Location: kernel/workqueue.c:634
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff810b54b3)
Location: kernel/workqueue.c:634
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct *work, int pool_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8940)
Location: kernel/workqueue.c:637
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
**Symbols:**

```
ffffffff810b8940-ffffffff810b8966: set_work_pool_and_clear_pending (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810c1533)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca993)
Location: kernel/workqueue.c:633
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5ac3)
Location: kernel/workqueue.c:633
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c73f2)
Location: kernel/workqueue.c:634
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da112)
Location: kernel/workqueue.c:651
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f188a)
Location: kernel/workqueue.c:653
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81114850)
Location: kernel/workqueue.c:653
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811207e0)
Location: kernel/workqueue.c:695
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff81129170)
Location: kernel/workqueue.c:692
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:process_one_work
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
void set_work_pool_and_clear_pending(struct work_struct *work, int pool_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011b8a8)
Location: kernel/workqueue.c:638
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
**Symbols:**

```
ffff80001011b8a8-ffff80001011b900: set_work_pool_and_clear_pending (STB_LOCAL)
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
In kernel/workqueue.c (c0372838)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (c000000000166888)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct *work, int pool_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d5d88)
Location: kernel/workqueue.c:638
Inline: False
Direct callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
```
**Symbols:**

```
ffffffe0000d5d88-ffffffe0000d5dda: set_work_pool_and_clear_pending (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810bb8a3)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff810aa341)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff810bae03)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
In kernel/workqueue.c (ffffffff810c42c3)
Location: kernel/workqueue.c:638
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
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
</ul>
