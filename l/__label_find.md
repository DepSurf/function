# Function: <code>__label_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *__label_find(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389400)
Location: security/apparmor/label.c:718
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81389400-ffffffff8138944f: __label_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *__label_find(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c3fc0)
Location: security/apparmor/label.c:718
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff813c3fc0-ffffffff813c400f: __label_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *__label_find(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813db550)
Location: security/apparmor/label.c:734
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff813db550-ffffffff813db59f: __label_find (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff813edab4)
Location: security/apparmor/label.c:732
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff8141559d)
Location: security/apparmor/label.c:732
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814479c5)
Location: security/apparmor/label.c:731
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff814648f5)
Location: security/apparmor/label.c:732
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff81491ee4)
Location: security/apparmor/label.c:728
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff814abe14)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff815086fa)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff815256ba)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff8152d9e5)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff8158bdd5)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff8162d46a)
Location: security/apparmor/label.c:757
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff816e1f4a)
Location: security/apparmor/label.c:757
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff8171b52a)
Location: security/apparmor/label.c:757
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff81759f7a)
Location: security/apparmor/label.c:765
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffff8000105a3268)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (c0753400)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (c00000000071e5e0)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffe0003ed6a2)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff814a43f4)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff81494e14)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff814a0494)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
In security/apparmor/label.c (ffffffff814b8b28)
Location: security/apparmor/label.c:755
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
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
