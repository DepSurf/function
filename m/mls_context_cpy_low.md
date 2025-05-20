# Function: <code>mls_context_cpy_low</code>

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
In security/selinux/ss/mls.c (ffffffff8135c781)
Location: security/selinux/ss/context.h:60
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff81392760)
Location: security/selinux/ss/context.h:60
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff813a9390)
Location: security/selinux/ss/context.h:60
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mls_context_cpy_low(struct context *dst, struct context *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813bfd8f)
Location: security/selinux/ss/context.h:60
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
Direct callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff813bee90-ffffffff813bef02: mls_context_cpy_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mls_context_cpy_low(struct context *dst, struct context *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813e5f2f)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
Direct callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff813e5030-ffffffff813e50a2: mls_context_cpy_low (STB_LOCAL)
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
In security/selinux/ss/mls.c (ffffffff81416c45)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff81433135)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff81460c07)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff8147a9b7)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff814cfe10)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff814ed33a)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff814f40d9)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff8154ea89)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff815e7bd5)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff816972c5)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff816cf7d9)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff8170bdf9)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffff80001056af20)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (c071eaa4)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (c0000000006cecf0)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffe0003bfc26)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff81472f97)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff814639b7)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff8146f037)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
In security/selinux/ss/mls.c (ffffffff814868a7)
Location: security/selinux/ss/context.h:61
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
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
