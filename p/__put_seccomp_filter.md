# Function: <code>__put_seccomp_filter</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115c4f0)
Location: kernel/seccomp.c:500
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff8115c4f0-ffffffff8115c535: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116b320)
Location: kernel/seccomp.c:509
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff8116b320-ffffffff8116b364: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811788e0)
Location: kernel/seccomp.c:569
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffffffff811788e0-ffffffff81178924: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81185670)
Location: kernel/seccomp.c:574
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff81185670-ffffffff811856b8: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81191590)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffffffff81191590-ffffffff811915d8: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a63c0)
Location: kernel/seccomp.c:585
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff811a63c0-ffffffff811a642b: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a39f0)
Location: kernel/seccomp.c:525
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff811a39f0-ffffffff811a3a61: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4600)
Location: kernel/seccomp.c:530
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff811a4600-ffffffff811a4671: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cde50)
Location: kernel/seccomp.c:533
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff811cde50-ffffffff811cdec1: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81201b50)
Location: kernel/seccomp.c:535
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff81201b50-ffffffff81201bdb: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81249940)
Location: kernel/seccomp.c:535
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff81249940-ffffffff812499cb: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81260c30)
Location: kernel/seccomp.c:535
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff81260c30-ffffffff81260cbb: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127ae00)
Location: kernel/seccomp.c:540
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff8127ae00-ffffffff8127ae8b: __put_seccomp_filter (STB_LOCAL)
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
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff8000102088b8)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffff8000102088b8-ffff80001020890c: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c04476b8)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
c04476b8-c0447708: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000285e10)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
c000000000285e10-c000000000285ea4: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016c250)
Location: kernel/seccomp.c:575
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
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
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81189bb0)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffffffff81189bb0-ffffffff81189bf8: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117ccf0)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffffffff8117ccf0-ffffffff8117cd38: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81187980)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffffffff81187980-ffffffff811879c8: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811952d0)
Location: kernel/seccomp.c:575
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_release
```
**Symbols:**

```
ffffffff811952d0-ffffffff81195318: __put_seccomp_filter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
