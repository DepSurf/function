# Function: <code>selinux_notify_policy_change</code>

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
void selinux_notify_policy_change(struct selinux_state *state, u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e59e0)
Location: security/selinux/ss/services.c:2178
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff814e59e0-ffffffff814e5a72: selinux_notify_policy_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void selinux_notify_policy_change(struct selinux_state *state, u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ec2c0)
Location: security/selinux/ss/services.c:2197
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff814ec2c0-ffffffff814ec35a: selinux_notify_policy_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void selinux_notify_policy_change(struct selinux_state *state, u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81546060)
Location: security/selinux/ss/services.c:2203
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff81546060-ffffffff815460fa: selinux_notify_policy_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void selinux_notify_policy_change(struct selinux_state *state, u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815de9a0)
Location: security/selinux/ss/services.c:2204
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff815de9a0-ffffffff815dea3d: selinux_notify_policy_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void selinux_notify_policy_change(struct selinux_state *state, u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168d6c0)
Location: security/selinux/ss/services.c:2197
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff8168d6c0-ffffffff8168d75d: selinux_notify_policy_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void selinux_notify_policy_change(u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c59a0)
Location: security/selinux/ss/services.c:2162
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff816c59a0-ffffffff816c5a2d: selinux_notify_policy_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void selinux_notify_policy_change(u32 seqno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817025f0)
Location: security/selinux/ss/services.c:2172
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff817025f0-ffffffff8170267d: selinux_notify_policy_change (STB_LOCAL)
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
<code>state, seqno</code> ➡️ <code>seqno</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
