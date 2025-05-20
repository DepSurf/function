# Function: <code>cn_netlink_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81541f60)
Location: drivers/connector/connector.c:133
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_exit_connector
```
**Symbols:**

```
ffffffff81541f60-ffffffff81541f7d: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff815938a0)
Location: drivers/connector/connector.c:133
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff815938a0-ffffffff815938bd: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff815c1160)
Location: drivers/connector/connector.c:133
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff815c1160-ffffffff815c117d: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff815d6ca0)
Location: drivers/connector/connector.c:133
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff815d6ca0-ffffffff815d6cbd: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff8163da80)
Location: drivers/connector/connector.c:133
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff8163da80-ffffffff8163da9d: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81679080)
Location: drivers/connector/connector.c:133
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81679080-ffffffff8167909d: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81698160)
Location: drivers/connector/connector.c:134
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81698160-ffffffff8169817d: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff816d0ce0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff816d0ce0-ffffffff816d0cff: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff816f4b00)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff816f4b00-ffffffff816f4b1f: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff817ad120)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff817ad120-ffffffff817ad13f: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff817c1cb0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff817c1cb0-ffffffff817c1ccf: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff817a51d0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff817a51d0-ffffffff817a51ef: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81830b50)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81830b50-ffffffff81830b6f: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81971f40)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81971f40-ffffffff81971f6c: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81add1d0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81add1d0-ffffffff81add1fc: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81b2b440)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81b2b440-ffffffff81b2b46c: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81b827d0)
Location: drivers/connector/connector.c:123
Inline: False
```
**Symbols:**

```
ffffffff81b827d0-ffffffff81b82804: cn_netlink_send (STB_GLOBAL)
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
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffff8000108ddf50)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffff8000108ddf50-ffff8000108ddfa0: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (c09ccf24)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
c09ccf24-c09ccf64: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (c0000000009717b0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
c0000000009717b0-c0000000009717dc: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffe00057442e)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffe00057442e-ffffffe000574474: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff816ba2f0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff816ba2f0-ffffffff816ba30f: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81697f30)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81697f30-ffffffff81697f4f: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff816e87c0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff816e87c0-ffffffff816e87df: cn_netlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cn_netlink_send(struct cn_msg *msg, u32 portid, u32 __group, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/connector/connector.c (ffffffff81702ec0)
Location: drivers/connector/connector.c:121
Inline: False
Direct callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
**Symbols:**

```
ffffffff81702ec0-ffffffff81702edf: cn_netlink_send (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
