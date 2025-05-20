# Function: <code>selinux_sctp_process_new_assoc</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_process_new_assoc(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5249
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
```
**Symbols:**

```
ffffffff815c7f30-ffffffff815c80ba: selinux_sctp_process_new_assoc (STB_LOCAL)
ffffffff81e8693f-ffffffff81e86960: selinux_sctp_process_new_assoc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_process_new_assoc(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5264
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
```
**Symbols:**

```
ffffffff81675010-ffffffff8167519a: selinux_sctp_process_new_assoc (STB_LOCAL)
ffffffff82073428-ffffffff82073449: selinux_sctp_process_new_assoc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_process_new_assoc(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5213
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
```
**Symbols:**

```
ffffffff816ad210-ffffffff816ad38f: selinux_sctp_process_new_assoc (STB_LOCAL)
ffffffff820f3031-ffffffff820f3052: selinux_sctp_process_new_assoc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_sctp_process_new_assoc(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e8e90)
Location: security/selinux/hooks.c:5309
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
```
**Symbols:**

```
ffffffff816e8e90-ffffffff816e9000: selinux_sctp_process_new_assoc (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
