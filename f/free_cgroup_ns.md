# Function: <code>free_cgroup_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81114da0)
Location: kernel/cgroup.c:5976
Inline: False
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - kernel/cgroup.c:cgroupns_put
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81114da0-ffffffff81114de2: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b5c0)
Location: kernel/cgroup.c:6343
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup.c:cgroupns_put
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8111b5c0-ffffffff8111b600: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81123900)
Location: kernel/cgroup.c:6382
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup.c:cgroupns_put
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81123900-ffffffff8112394e: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81128cb0)
Location: kernel/cgroup/namespace.c:39
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81128cb0-ffffffff81128d37: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff811358c0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff811358c0-ffffffff81135947: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff811441d0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff811441d0-ffffffff81144257: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8114fce0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8114fce0-ffffffff8114fd67: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8115bbe0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8115bbe0-ffffffff8115bc6c: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81167800)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81167800-ffffffff8116788c: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81179090)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81179090-ffffffff8117911c: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81175da0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81175da0-ffffffff81175e4f: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81176920)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81176920-ffffffff811769cf: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8119e1a0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8119e1a0-ffffffff8119e24f: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff811ce550)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff811ce550-ffffffff811ce606: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81211d90)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81211d90-ffffffff81211e46: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff812276f0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff812276f0-ffffffff812277a6: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8123f500)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8123f500-ffffffff8123f5b6: free_cgroup_ns (STB_GLOBAL)
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
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffff8000101da038)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffff8000101da038-ffff8000101da178: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (c041c960)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
c041c960-c041ca14: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (c0000000002471f0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
c0000000002471f0-c000000000247328: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffe000152794)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffe000152794-ffffffe00015283c: free_cgroup_ns (STB_GLOBAL)
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
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8115fe20)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8115fe20-ffffffff8115feac: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff81153090)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff81153090-ffffffff8115311c: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8115dbf0)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8115dbf0-ffffffff8115dc7c: free_cgroup_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/namespace.c (ffffffff8116ae50)
Location: kernel/cgroup/namespace.c:40
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
**Symbols:**

```
ffffffff8116ae50-ffffffff8116aedc: free_cgroup_ns (STB_GLOBAL)
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
