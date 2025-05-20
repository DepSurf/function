# Function: <code>lsm_task_alloc</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lsm_task_alloc(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139da60)
Location: security/security.c:488
Inline: False
Direct callers:
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff8139da60-ffffffff8139db8c: lsm_task_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lsm_task_alloc(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3360)
Location: security/security.c:452
Inline: False
Direct callers:
  - security/security.c:security_task_alloc
```
**Symbols:**

```
ffffffff813c3360-ffffffff813c3496: lsm_task_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410775)
Location: security/security.c:569
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff8143df15)
Location: security/security.c:568
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff814579c5)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff814aa7ff)
Location: security/security.c:655
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff814c7dff)
Location: security/security.c:657
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff814ce43f)
Location: security/security.c:660
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff815270ff)
Location: security/security.c:660
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff815bbd92)
Location: security/security.c:688
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81667c52)
Location: security/security.c:737
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff816a0272)
Location: security/security.c:745
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff816dcc83)
Location: security/security.c:750
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffff800010543690)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (c06f95f8)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (c0000000006977b8)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffe00039fb72)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff8144ffa5)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff814409f5)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff8144c045)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff81463415)
Location: security/security.c:602
Inline: True
Inline callers:
  - security/security.c:security_task_alloc
  - security/security.c:ordered_lsm_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
