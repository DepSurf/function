# Function: <code>find_task_by_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e730)
Location: kernel/pid.c:452
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff8109e730-ffffffff8109e758: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1e2a)
Location: kernel/pid.c:452
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810a1dd0-ffffffff810a1df8: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6eea)
Location: kernel/pid.c:452
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810a6e90-ffffffff810a6eb8: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3e2c)
Location: kernel/pid.c:453
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810a3dd0-ffffffff810a3e00: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa430)
Location: kernel/pid.c:322
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810aa3c0-ffffffff810aa3fa: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b103e)
Location: kernel/pid.c:334
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810b0fd0-ffffffff810b100a: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ba17e)
Location: kernel/pid.c:343
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810ba110-ffffffff810ba146: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c008a)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810c0020-ffffffff810c0056: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c645a)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810c63f0-ffffffff810c6426: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce381)
Location: kernel/pid.c:412
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff810ce2c0-ffffffff810ce2f1: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8e3d)
Location: kernel/pid.c:413
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff810c8d90-ffffffff810c8dc0: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca8dd)
Location: kernel/pid.c:413
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff810ca830-ffffffff810ca860: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd82d)
Location: kernel/pid.c:413
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff810dd780-ffffffff810dd7b0: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7192)
Location: kernel/pid.c:413
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff810f70c0-ffffffff810f70f9: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119902)
Location: kernel/pid.c:413
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/bpf/helpers.c:bpf_task_from_pid
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff81119810-ffffffff81119849: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126de2)
Location: kernel/pid.c:416
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/bpf/helpers.c:bpf_task_from_pid
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff81126cf0-ffffffff81126d29: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811313c2)
Location: kernel/pid.c:416
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/bpf/helpers.c:bpf_task_from_pid
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
```
**Symbols:**

```
ffffffff811312d0-ffffffff81131309: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124cb8)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffff800010124c40-ffff800010124c88: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377c4c)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
c0377be0-c0377c20: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016eab4)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
c00000000016e9f0-c00000000016ea64: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcc44)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffe0000dcbce-ffffffe0000dcc1a: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c07da)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810c0770-ffffffff810c07a6: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aefda)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810aef70-ffffffff810aefa6: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfd2a)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810bfcc0-ffffffff810bfcf6: find_task_by_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_pid_ns(pid_t nr, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c813a)
Location: kernel/pid.c:346
Inline: True
Inline callers:
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_lookup
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
**Symbols:**

```
ffffffff810c80d0-ffffffff810c8106: find_task_by_pid_ns (STB_GLOBAL)
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
