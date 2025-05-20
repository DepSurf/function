# Function: <code>__kobject_del</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eac60)
Location: lib/kobject.c:602
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff815eac60-ffffffff815ead2e: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f580)
Location: lib/kobject.c:602
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff8160f580-ffffffff8160f644: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2cc0)
Location: lib/kobject.c:602
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff815f2cc0-ffffffff815f2d84: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165fea0)
Location: lib/kobject.c:602
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff8165fea0-ffffffff8165ff61: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779980)
Location: lib/kobject.c:570
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff81779980-ffffffff81779a50: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022950)
Location: lib/kobject.c:578
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff82022950-ffffffff82022a30: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a29c0)
Location: lib/kobject.c:579
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff820a29c0-ffffffff820a2aa0: __kobject_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kobject_del(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217aa40)
Location: lib/kobject.c:586
Inline: False
Direct callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_cleanup
```
**Symbols:**

```
ffffffff8217aa40-ffffffff8217ab20: __kobject_del (STB_LOCAL)
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
