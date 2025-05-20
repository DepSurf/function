# Function: <code>selinux_policy_cancel</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8f10)
Location: security/selinux/ss/services.c:2165
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814e8f10-ffffffff814e8f72: selinux_policy_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef840)
Location: security/selinux/ss/services.c:2184
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814ef840-ffffffff814ef8a2: selinux_policy_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81549c70)
Location: security/selinux/ss/services.c:2190
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81549c70-ffffffff81549cd2: selinux_policy_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e28d0)
Location: security/selinux/ss/services.c:2191
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff815e28d0-ffffffff815e293a: selinux_policy_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81691aa0)
Location: security/selinux/ss/services.c:2184
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81691aa0-ffffffff81691b0a: selinux_policy_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816ca030)
Location: security/selinux/ss/services.c:2149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff816ca030-ffffffff816ca09b: selinux_policy_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void selinux_policy_cancel(struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706c40)
Location: security/selinux/ss/services.c:2159
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81706c40-ffffffff81706cab: selinux_policy_cancel (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, load_state</code> ➡️ <code>load_state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
