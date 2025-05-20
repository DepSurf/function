# Function: <code>insert_entry</code>

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
In fs/proc/proc_sysctl.c (ffffffff81285561)
Location: fs/proc/proc_sysctl.c:133
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812b26a1)
Location: fs/proc/proc_sysctl.c:133
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812c7ef1)
Location: fs/proc/proc_sysctl.c:133
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812d5266)
Location: fs/proc/proc_sysctl.c:134
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812f9aa6)
Location: fs/proc/proc_sysctl.c:135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff81326855)
Location: fs/proc/proc_sysctl.c:135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8133d6a5)
Location: fs/proc/proc_sysctl.c:135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff813661da)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8137e46a)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:141
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813c7010-ffffffff813c7104: insert_entry (STB_LOCAL)
ffffffff813c9680-ffffffff813c96b6: insert_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:142
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813d8fe0-ffffffff813d90d4: insert_entry (STB_LOCAL)
ffffffff81bec00f-ffffffff81bec045: insert_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:137
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813dfe90-ffffffff813dff83: insert_entry (STB_LOCAL)
ffffffff81bde060-ffffffff81bde096: insert_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:137
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81431820-ffffffff81431913: insert_entry (STB_LOCAL)
ffffffff81cc8477-ffffffff81cc84ad: insert_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:158
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814abc00-ffffffff814abd01: insert_entry (STB_LOCAL)
ffffffff81e7b078-ffffffff81e7b0ae: insert_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815428a0)
Location: fs/proc/proc_sysctl.c:151
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815428a0-ffffffff81542a06: insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157a970)
Location: fs/proc/proc_sysctl.c:143
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8157a970-ffffffff8157aad6: insert_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insert_entry(struct ctl_table_header *head, struct ctl_table *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b3250)
Location: fs/proc/proc_sysctl.c:143
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815b3250-ffffffff815b33b6: insert_entry (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffff80001044aed0)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (c0610254)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (c000000000562de8)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffe0002e00a4)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff81376a4a)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8136751a)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff8137451a)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff81387f2a)
Location: fs/proc/proc_sysctl.c:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
