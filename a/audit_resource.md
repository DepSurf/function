# Function: <code>audit_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813873f0)
Location: security/apparmor/resource.c:50
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff813873f0-ffffffff81387483: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813c1e90)
Location: security/apparmor/resource.c:50
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff813c1e90-ffffffff813c1f23: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813d9330)
Location: security/apparmor/resource.c:50
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff813d9330-ffffffff813d93c3: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813ea580)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff813ea580-ffffffff813ea62b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81411e80)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81411e80-ffffffff81411f2b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81444040)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81444040-ffffffff814440eb: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814610f0)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff814610f0-ffffffff8146119b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff8148e3f0)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff8148e3f0-ffffffff8148e48b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814a82b0)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff814a82b0-ffffffff814a834b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81505630)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81505630-ffffffff815056cb: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81522760)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81522760-ffffffff815227fb: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81528940)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81528940-ffffffff815289db: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81586be0)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81586be0-ffffffff81586c7b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81626f80)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81626f80-ffffffff8162705f: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_resource(const struct cred *subj_cred, struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff816daf70)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff816daf70-ffffffff816db042: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_resource(const struct cred *subj_cred, struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81714680)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81714680-ffffffff8171473f: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_resource(const struct cred *subj_cred, struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81753090)
Location: security/apparmor/resource.c:56
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff81753090-ffffffff8175314f: audit_resource (STB_LOCAL)
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
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffff80001059e960)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffff80001059e960-ffff80001059ea38: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (c074f714)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
c074f714-c074f7e0: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (c000000000718400)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
c000000000718400-c000000000718510: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffe0003e9e4c)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffe0003e9e4c-ffffffe0003e9ef8: audit_resource (STB_LOCAL)
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
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814a0890)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff814a0890-ffffffff814a092b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814912b0)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff814912b0-ffffffff8149134b: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff8149c930)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff8149c930-ffffffff8149c9cb: audit_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_resource(struct aa_profile *profile, unsigned int resource, long unsigned int value, struct aa_label *peer, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814b4ec0)
Location: security/apparmor/resource.c:52
Inline: False
Direct callers:
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
```
**Symbols:**

```
ffffffff814b4ec0-ffffffff814b4f5b: audit_resource (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_label *peer</code>
</li>
<li>
<b>Param added. </b>
<code>const char *info</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, resource, value, error</code> ➡️ <code>profile, resource, value, peer, info, error</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, resource, value, peer, info, error</code> ➡️ <code>subj_cred, profile, resource, value, peer, info, error</code>
</li>
</ul>
</details>
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
