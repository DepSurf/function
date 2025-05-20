# Function: <code>selinux_policy_commit</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2189
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81bf1027-ffffffff81bf1059: selinux_policy_commit.cold (STB_LOCAL)
ffffffff814e8f80-ffffffff814e9073: selinux_policy_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2209
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81be3149-ffffffff81be3184: selinux_policy_commit.cold (STB_LOCAL)
ffffffff814ef8b0-ffffffff814efaf6: selinux_policy_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2215
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81cd4fee-ffffffff81cd503d: selinux_policy_commit.cold (STB_LOCAL)
ffffffff81549ce0-ffffffff81549f85: selinux_policy_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2216
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81e87e2a-ffffffff81e87e79: selinux_policy_commit.cold (STB_LOCAL)
ffffffff815e2940-ffffffff815e2c08: selinux_policy_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_state *state, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2209
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff82073d4e-ffffffff82073d62: selinux_policy_commit.cold (STB_LOCAL)
ffffffff81691b20-ffffffff81691e19: selinux_policy_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2173
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff820f3911-ffffffff820f3925: selinux_policy_commit.cold (STB_LOCAL)
ffffffff816ca0b0-ffffffff816ca39b: selinux_policy_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void selinux_policy_commit(struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2183
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff821d0ad7-ffffffff821d0aeb: selinux_policy_commit.cold (STB_LOCAL)
ffffffff81706cc0-ffffffff81706fab: selinux_policy_commit (STB_GLOBAL)
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
