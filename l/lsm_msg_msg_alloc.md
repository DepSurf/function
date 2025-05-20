# Function: <code>lsm_msg_msg_alloc</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lsm_msg_msg_alloc(struct msg_msg *mp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139ff9e)
Location: security/security.c:609
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff8139dcb0-ffffffff8139dcec: lsm_msg_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lsm_msg_msg_alloc(struct msg_msg *mp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5c53)
Location: security/security.c:565
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff813c35d0-ffffffff813c360d: lsm_msg_msg_alloc (STB_GLOBAL)
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
In security/security.c (ffffffff814110e5)
Location: security/security.c:611
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff8143e935)
Location: security/security.c:610
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff81458325)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff814ab185)
Location: security/security.c:708
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff814c878e)
Location: security/security.c:710
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff814cedce)
Location: security/security.c:713
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff81527a8e)
Location: security/security.c:713
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff815bca0e)
Location: security/security.c:741
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff81668c8e)
Location: security/security.c:790
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff816a128e)
Location: security/security.c:798
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff816ddb0e)
Location: security/security.c:815
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffff8000105441a4)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (c06fa0a8)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (c000000000698c34)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffe0003a03d4)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff81450905)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff81441355)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff8144c9a5)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
In security/security.c (ffffffff81463d75)
Location: security/security.c:644
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
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
