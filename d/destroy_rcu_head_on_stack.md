# Function: <code>destroy_rcu_head_on_stack</code>

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
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:459
Inline: True
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
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:470
Inline: True
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
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:475
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:226
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:226
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:232
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:232
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:210
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:210
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:228
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:228
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112bd41)
Location: include/linux/rcupdate.h:243
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:243
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c1d1)
Location: include/linux/rcupdate.h:249
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:249
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114cd61)
Location: include/linux/rcupdate.h:249
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:249
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81172af0)
Location: include/linux/rcupdate.h:251
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:251
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a94b0)
Location: include/linux/rcupdate.h:309
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:309
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bb22e)
Location: include/linux/rcupdate.h:285
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cb1ee)
Location: include/linux/rcupdate.h:280
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
```
In kernel/rcu/srcutree.c (0)
Location: include/linux/rcupdate.h:195
Inline: True
```
</details>
</li>
</ul>

## Differences
