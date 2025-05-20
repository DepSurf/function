# Function: <code>destroy_pid_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8111f550)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
```
**Symbols:**

```
ffffffff8111f550-ffffffff8111f5be: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81127490)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
```
**Symbols:**

```
ffffffff81127490-ffffffff811274fc: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81131020)
Location: kernel/pid_namespace.c:162
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
```
**Symbols:**

```
ffffffff81131020-ffffffff81131072: destroy_pid_namespace (STB_LOCAL)
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
In kernel/pid_namespace.c (ffffffff811326dc)
Location: kernel/pid_namespace.c:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8113f3a0)
Location: kernel/pid_namespace.c:160
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff8113f3a0-ffffffff8113f3d4: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8114dce0)
Location: kernel/pid_namespace.c:141
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff8114dce0-ffffffff8114dd14: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8115a9b0)
Location: kernel/pid_namespace.c:141
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff8115a9b0-ffffffff8115a9e4: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81167060)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff81167060-ffffffff81167094: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81172f20)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff81172f20-ffffffff81172f54: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811851e0)
Location: kernel/pid_namespace.c:133
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81181fde)
Location: kernel/pid_namespace.c:133
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff8118312e)
Location: kernel/pid_namespace.c:133
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff811ab1de)
Location: kernel/pid_namespace.c:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff811dc918)
Location: kernel/pid_namespace.c:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff81222258)
Location: kernel/pid_namespace.c:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff81238888)
Location: kernel/pid_namespace.c:137
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff81252558)
Location: kernel/pid_namespace.c:138
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffff8000101e7278)
Location: kernel/pid_namespace.c:142
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (c0427750)
Location: kernel/pid_namespace.c:142
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (c000000000257a20)
Location: kernel/pid_namespace.c:142
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffe00015c7b0)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffe00015c7b0-ffffffe00015c7fc: destroy_pid_namespace (STB_LOCAL)
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
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8116b540)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff8116b540-ffffffff8116b574: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8115e740)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff8115e740-ffffffff8115e774: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81169310)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff81169310-ffffffff81169344: destroy_pid_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81176a00)
Location: kernel/pid_namespace.c:142
Inline: False
Direct callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
**Symbols:**

```
ffffffff81176a00-ffffffff81176a34: destroy_pid_namespace (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
