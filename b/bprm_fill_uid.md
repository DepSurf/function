# Function: <code>bprm_fill_uid</code>

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
In fs/exec.c (ffffffff812129d2)
Location: fs/exec.c:1299
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
In fs/exec.c (ffffffff812397b5)
Location: fs/exec.c:1446
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
In fs/exec.c (ffffffff8124c4f5)
Location: fs/exec.c:1472
Inline: True
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
In fs/exec.c (ffffffff81258605)
Location: fs/exec.c:1504
Inline: True
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
In fs/exec.c (ffffffff8127a3f5)
Location: fs/exec.c:1506
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812a0fa8)
Location: fs/exec.c:1520
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812b5fa8)
Location: fs/exec.c:1524
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812d2d35)
Location: fs/exec.c:1525
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812e4845)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bprm_fill_uid(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131c0f0)
Location: fs/exec.c:1620
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8131c0f0-ffffffff8131c1eb: bprm_fill_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bprm_fill_uid(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813275e0)
Location: fs/exec.c:1587
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813275e0-ffffffff813276db: bprm_fill_uid (STB_LOCAL)
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
In fs/exec.c (ffffffff8132f8b0)
Location: fs/exec.c:1584
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
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
In fs/exec.c (ffffffff8137d060)
Location: fs/exec.c:1586
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bprm_fill_uid(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813f9d30)
Location: fs/exec.c:1591
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813f9d30-ffffffff813f9ed1: bprm_fill_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bprm_fill_uid(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81483620)
Location: fs/exec.c:1596
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81483620-ffffffff814837c6: bprm_fill_uid (STB_LOCAL)
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
In fs/exec.c (ffffffff814bb550)
Location: fs/exec.c:1599
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
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
In fs/exec.c (ffffffff814edac0)
Location: fs/exec.c:1644
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
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
In fs/exec.c (ffff80001038c108)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (c0574098)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (c000000000483ce8)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffe00025d68e)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812dce25)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812cdaa5)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812dac35)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
In fs/exec.c (ffffffff812ebb35)
Location: fs/exec.c:1526
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
