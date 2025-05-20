# Function: <code>apparmor_secmark_init</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_secmark_init(struct aa_secmark *secmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8150eb40)
Location: security/apparmor/net.c:258
Inline: False
Direct callers:
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff8150eb40-ffffffff8150ebad: apparmor_secmark_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_secmark_init(struct aa_secmark *secmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8152b9b0)
Location: security/apparmor/net.c:260
Inline: False
Direct callers:
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff8152b9b0-ffffffff8152ba1d: apparmor_secmark_init (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff81532750)
Location: security/apparmor/net.c:260
Inline: True
Inline callers:
  - security/apparmor/net.c:apparmor_secmark_check
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
In security/apparmor/net.c (ffffffff81590cd0)
Location: security/apparmor/net.c:260
Inline: True
Inline callers:
  - security/apparmor/net.c:apparmor_secmark_check
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
In security/apparmor/net.c (ffffffff81631eb8)
Location: security/apparmor/net.c:261
Inline: True
Inline callers:
  - security/apparmor/net.c:apparmor_secmark_check
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
In security/apparmor/net.c (ffffffff816e6c3d)
Location: security/apparmor/net.c:267
Inline: True
Inline callers:
  - security/apparmor/net.c:apparmor_secmark_check
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
In security/apparmor/net.c (ffffffff8172039c)
Location: security/apparmor/net.c:267
Inline: True
Inline callers:
  - security/apparmor/net.c:apparmor_secmark_check
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
In security/apparmor/net.c (ffffffff8175ee1c)
Location: security/apparmor/net.c:270
Inline: True
Inline callers:
  - security/apparmor/net.c:apparmor_secmark_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
