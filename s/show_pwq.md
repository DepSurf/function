# Function: <code>show_pwq</code>

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
In kernel/workqueue.c (ffffffff8109cbfb)
Location: kernel/workqueue.c:4200
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff8109fd02)
Location: kernel/workqueue.c:4298
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810a4bd2)
Location: kernel/workqueue.c:4328
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810a1ce4)
Location: kernel/workqueue.c:4348
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810a8564)
Location: kernel/workqueue.c:4375
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810b03fc)
Location: kernel/workqueue.c:4453
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810b953c)
Location: kernel/workqueue.c:4476
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810bf22a)
Location: kernel/workqueue.c:4621
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810c568b)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ccd90)
Location: kernel/workqueue.c:4677
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff810ccd90-ffffffff810cd031: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81bdbbe5)
Location: kernel/workqueue.c:4690
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81bdbbe5-ffffffff81bdbe86: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81bcdc9d)
Location: kernel/workqueue.c:4697
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81bcdc9d-ffffffff81bcdf3d: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81ca4d30)
Location: kernel/workqueue.c:4736
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81ca4d30-ffffffff81ca4ffe: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81e5460d)
Location: kernel/workqueue.c:4719
Inline: False
Direct callers:
  - kernel/workqueue.c:show_one_workqueue
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81e5460d-ffffffff81e548dc: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81111e40)
Location: kernel/workqueue.c:4728
Inline: False
Direct callers:
  - kernel/workqueue.c:show_one_workqueue
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81111e40-ffffffff8111221e: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111dda0)
Location: kernel/workqueue.c:5096
Inline: False
Direct callers:
  - kernel/workqueue.c:show_one_workqueue
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff8111dda0-ffffffff8111e180: show_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81127ad0)
Location: kernel/workqueue.c:5119
Inline: False
Direct callers:
  - kernel/workqueue.c:show_one_workqueue
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81127ad0-ffffffff81127eb0: show_pwq (STB_LOCAL)
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
In kernel/workqueue.c (ffff800010122274)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (c0375c28)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (c00000000016bcb4)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffe0000dabb2)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810bf9fb)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810ae21b)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810bef5b)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
In kernel/workqueue.c (ffffffff810c72c6)
Location: kernel/workqueue.c:4654
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
