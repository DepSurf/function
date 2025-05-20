# Function: <code>__first_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *__first_profile(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81374c30)
Location: security/apparmor/apparmorfs.c:831
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff81374c30-ffffffff81374cde: __first_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *__first_profile(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ab030)
Location: security/apparmor/apparmorfs.c:1325
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff813ab030-ffffffff813ab0ef: __first_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *__first_profile(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c1bb0)
Location: security/apparmor/apparmorfs.c:1431
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff813c1bb0-ffffffff813c1c74: __first_profile (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff813d9ae4)
Location: security/apparmor/apparmorfs.c:1952
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff81400c0b)
Location: security/apparmor/apparmorfs.c:2016
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814320e4)
Location: security/apparmor/apparmorfs.c:2013
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8144deb2)
Location: security/apparmor/apparmorfs.c:2011
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8147b822)
Location: security/apparmor/apparmorfs.c:2016
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814954f2)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814ed5a8)
Location: security/apparmor/apparmorfs.c:2103
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8150ac28)
Location: security/apparmor/apparmorfs.c:2100
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff815113a4)
Location: security/apparmor/apparmorfs.c:2101
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8156efa4)
Location: security/apparmor/apparmorfs.c:2101
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8160d8e2)
Location: security/apparmor/apparmorfs.c:2121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816bfdf2)
Location: security/apparmor/apparmorfs.c:2310
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816f88f2)
Location: security/apparmor/apparmorfs.c:2358
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff817356b8)
Location: security/apparmor/apparmorfs.c:2356
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffff80001058b578)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (c073c140)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (c0000000006fc96c)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffe0003d9c30)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8148dad2)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff8147e4f2)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff81489b72)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
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
In security/apparmor/apparmorfs.c (ffffffff814a17fa)
Location: security/apparmor/apparmorfs.c:1984
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
