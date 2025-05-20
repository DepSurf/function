# Function: <code>kobject_uevent_net_broadcast</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81975a9c)
Location: lib/kobject_uevent.c:297
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d214d)
Location: lib/kobject_uevent.c:379
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0b4f5)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a7aee1)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ab2241)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ec440)
Location: lib/kobject_uevent.c:380
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff815ec440-ffffffff815ec4db: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81610c20)
Location: lib/kobject_uevent.c:380
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81610c20-ffffffff81610cbb: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815f4110)
Location: lib/kobject_uevent.c:381
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff815f4110-ffffffff815f432d: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81661480)
Location: lib/kobject_uevent.c:381
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81661480-ffffffff8166169d: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8177b230)
Location: lib/kobject_uevent.c:381
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8177b230-ffffffff8177b453: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff82024440)
Location: lib/kobject_uevent.c:381
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff82024440-ffffffff82024663: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a4550)
Location: lib/kobject_uevent.c:381
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff820a4550-ffffffff820a4773: kobject_uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_uevent_net_broadcast(struct kobject *kobj, struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217c620)
Location: lib/kobject_uevent.c:381
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8217c620-ffffffff8217c843: kobject_uevent_net_broadcast (STB_LOCAL)
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
In lib/kobject_uevent.c (ffff800010d8c43c)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (c0e86800)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (c000000000ece418)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffe0008b55f2)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a51091)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0e191)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81abd481)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ac9901)
Location: lib/kobject_uevent.c:380
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
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
