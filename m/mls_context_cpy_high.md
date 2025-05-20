# Function: <code>mls_context_cpy_high</code>

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
In security/selinux/ss/mls.c (ffffffff8135c900)
Location: security/selinux/ss/context.h:80
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff813928da)
Location: security/selinux/ss/context.h:80
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff813a950a)
Location: security/selinux/ss/context.h:80
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mls_context_cpy_high(struct context *dst, struct context *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813bee10)
Location: security/selinux/ss/context.h:80
Inline: False
Direct callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff813bee10-ffffffff813bee82: mls_context_cpy_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mls_context_cpy_high(struct context *dst, struct context *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/mls.c (ffffffff813e4fb0)
Location: security/selinux/ss/context.h:81
Inline: False
Direct callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff813e4fb0-ffffffff813e5022: mls_context_cpy_high (STB_LOCAL)
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
In security/selinux/ss/mls.c (ffffffff81416d3c)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff81433245)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff81460cf4)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff8147aaa4)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff814d0028)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff814ed553)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff814f42e1)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff8154ec91)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff815e7ddd)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff816974cd)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff816cf944)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff8170bf64)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffff80001056b030)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (c071eb08)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (c0000000006cedfc)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffe0003bfd72)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff81473084)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff81463aa4)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff8146f124)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff81486994)
Location: security/selinux/ss/context.h:81
Inline: True
Inline callers:
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
