# Function: <code>audit_set_feature</code>

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
In kernel/audit.c (ffffffff81123138)
Location: kernel/audit.c:755
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8112acc0)
Location: kernel/audit.c:752
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff811349e0)
Location: kernel/audit.c:892
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81135f0f)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81142c5f)
Location: kernel/audit.c:1068
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8115186a)
Location: kernel/audit.c:1112
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8115e51a)
Location: kernel/audit.c:1109
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116a7ed)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_set_feature(struct audit_features *uaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188b80)
Location: kernel/audit.c:1131
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81188b80-ffffffff81188ce9: audit_set_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_set_feature(struct audit_features *uaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185ee0)
Location: kernel/audit.c:1135
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81185ee0-ffffffff81186049: audit_set_feature (STB_LOCAL)
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
In kernel/audit.c (0)
Location: kernel/audit.c:1135
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1157
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1139
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1137
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1137
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1148
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffe00015fd60)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (0)
Location: kernel/audit.c:1103
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
</ul>
