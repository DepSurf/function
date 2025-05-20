# Function: <code>__regset_get</code>

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
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff810d4ff0)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff810d4ff0-ffffffff810d50cb: __regset_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff810d6cd0)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff810d6cd0-ffffffff810d6dab: __regset_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff810ea570)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff810ea570-ffffffff810ea64b: __regset_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff811052a0)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff811052a0-ffffffff811053a7: __regset_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff8112ad10)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff8112ad10-ffffffff8112ae17: __regset_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff81137f80)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff81137f80-ffffffff81138087: __regset_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __regset_get(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff81143190)
Location: kernel/regset.c:6
Inline: False
Direct callers:
  - kernel/regset.c:copy_regset_to_user
  - kernel/regset.c:regset_get
```
**Symbols:**

```
ffffffff81143190-ffffffff81143297: __regset_get (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
