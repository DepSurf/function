# Function: <code>nvm_rq_dev_to_tgt</code>

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
void nvm_rq_dev_to_tgt(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d77f0)
Location: drivers/lightnvm/core.c:496
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff815d77f0-ffffffff815d781e: nvm_rq_dev_to_tgt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvm_rq_dev_to_tgt(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163e5e0)
Location: drivers/lightnvm/core.c:517
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff8163e5e0-ffffffff8163e60e: nvm_rq_dev_to_tgt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvm_rq_dev_to_tgt(struct nvm_tgt_dev *tgt_dev, struct nvm_rq *rqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81679c80)
Location: drivers/lightnvm/core.c:609
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
```
**Symbols:**

```
ffffffff81679c80-ffffffff81679cae: nvm_rq_dev_to_tgt (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff816992f5)
Location: drivers/lightnvm/core.c:611
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816d1d76)
Location: drivers/lightnvm/core.c:613
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816f5c66)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817ae9b6)
Location: drivers/lightnvm/core.c:617
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817c3536)
Location: drivers/lightnvm/core.c:613
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff817a68c6)
Location: drivers/lightnvm/core.c:613
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/lightnvm/core.c (ffff8000108df138)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (c09ce5c4)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (c000000000973260)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffe0005755ea)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff816bb456)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9926)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
In drivers/lightnvm/core.c (ffffffff81704166)
Location: drivers/lightnvm/core.c:618
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_end_io
  - drivers/lightnvm/core.c:nvm_submit_io
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
