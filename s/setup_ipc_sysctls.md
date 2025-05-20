# Function: <code>setup_ipc_sysctls</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool setup_ipc_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff8159f4b0)
Location: ipc/ipc_sysctl.c:214
Inline: False
Direct callers:
  - ipc/ipc_sysctl.c:ipc_sysctl_init
```
**Symbols:**

```
ffffffff8159f4b0-ffffffff8159f69d: setup_ipc_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool setup_ipc_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff81648cd0)
Location: ipc/ipc_sysctl.c:214
Inline: False
Direct callers:
  - ipc/ipc_sysctl.c:ipc_sysctl_init
```
**Symbols:**

```
ffffffff81648cd0-ffffffff81648ebd: setup_ipc_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool setup_ipc_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff81681230)
Location: ipc/ipc_sysctl.c:214
Inline: False
Direct callers:
  - ipc/ipc_sysctl.c:ipc_sysctl_init
```
**Symbols:**

```
ffffffff81681230-ffffffff8168141d: setup_ipc_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool setup_ipc_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff816bd650)
Location: ipc/ipc_sysctl.c:214
Inline: False
Direct callers:
  - ipc/ipc_sysctl.c:ipc_sysctl_init
```
**Symbols:**

```
ffffffff816bd650-ffffffff816bd842: setup_ipc_sysctls (STB_GLOBAL)
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
