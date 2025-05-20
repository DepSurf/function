# Function: <code>free_proxy</code>

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
In security/apparmor/label.c (ffffffff813898e5)
Location: security/apparmor/label.c:46
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff813c44d5)
Location: security/apparmor/label.c:46
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff813dbae5)
Location: security/apparmor/label.c:46
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_proxy(struct aa_proxy *proxy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecd70)
Location: security/apparmor/label.c:46
Inline: False
Direct callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff813ecd70-ffffffff813ecdb3: free_proxy (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff81414575)
Location: security/apparmor/label.c:46
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81446915)
Location: security/apparmor/label.c:46
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81463785)
Location: security/apparmor/label.c:46
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81490a35)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff814aa8f5)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81509145)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81526105)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff8152ba95)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81589e75)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff8162b035)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff816df8b5)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81718f05)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff81757995)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void free_proxy(struct aa_proxy *proxy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1a50)
Location: security/apparmor/label.c:42
Inline: False
Direct callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffff8000105a1a50-ffff8000105a1ab0: free_proxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_proxy(struct aa_proxy *proxy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c07521b0)
Location: security/apparmor/label.c:42
Inline: False
Direct callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
c07521b0-c0752210: free_proxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_proxy(struct aa_proxy *proxy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071c6f0)
Location: security/apparmor/label.c:42
Inline: False
Direct callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
c00000000071c6f0-c00000000071c788: free_proxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_proxy(struct aa_proxy *proxy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec2be)
Location: security/apparmor/label.c:42
Inline: False
Direct callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffe0003ec2be-ffffffe0003ec31a: free_proxy (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff814a2ed5)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff814938f5)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff8149ef75)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
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
In security/apparmor/label.c (ffffffff814b75a5)
Location: security/apparmor/label.c:42
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_proxy_kref
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
