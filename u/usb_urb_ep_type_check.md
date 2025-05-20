# Function: <code>usb_urb_ep_type_check</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171e0b0)
Location: drivers/usb/core/urb.c:202
Inline: True
```
**Symbols:**

```
ffffffff8171e0b0-ffffffff8171e10c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175d0c6)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff8175ce40-ffffffff8175ce9c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817816f6)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff81781470-ffffffff817814cc: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817bfc1b)
Location: drivers/usb/core/urb.c:201
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff817bf850-ffffffff817bf8ac: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f059b)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff817f01d0-ffffffff817f022c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818bf890)
Location: drivers/usb/core/urb.c:202
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff818bf890-ffffffff818bf8ec: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818cc4d0)
Location: drivers/usb/core/urb.c:224
Inline: False
```
**Symbols:**

```
ffffffff818cc4d0-ffffffff818cc52c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818af9f0)
Location: drivers/usb/core/urb.c:224
Inline: False
```
**Symbols:**

```
ffffffff818af9f0-ffffffff818afa4c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81944b40)
Location: drivers/usb/core/urb.c:224
Inline: False
```
**Symbols:**

```
ffffffff81944b40-ffffffff81944b93: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81a9d310)
Location: drivers/usb/core/urb.c:224
Inline: False
```
**Symbols:**

```
ffffffff81a9d310-ffffffff81a9d37b: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c223d0)
Location: drivers/usb/core/urb.c:225
Inline: False
```
**Symbols:**

```
ffffffff81c223d0-ffffffff81c2243b: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c89340)
Location: drivers/usb/core/urb.c:225
Inline: False
```
**Symbols:**

```
ffffffff81c89340-ffffffff81c893ab: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81d3dd90)
Location: drivers/usb/core/urb.c:225
Inline: False
```
**Symbols:**

```
ffffffff81d3dd90-ffffffff81d3ddfb: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffff800010a20144)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffff800010a1fe78-ffff800010a1fee8: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c0af7344)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
c0af6f14-c0af6f78: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c000000000ada40c)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
c000000000ad9eb0-c000000000ad9f18: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe0006434b2)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffe0006430fa-ffffffe00064315c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a897b)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff817a85b0-ffffffff817a860c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179a38b)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff81799fc0-ffffffff8179a01c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e541b)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff817e5050-ffffffff817e50ac: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int usb_urb_ep_type_check(const struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817ff67b)
Location: drivers/usb/core/urb.c:202
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
**Symbols:**

```
ffffffff817ff2b0-ffffffff817ff30c: usb_urb_ep_type_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
