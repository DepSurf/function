# Function: <code>alloc_uevent_skb</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d1d00)
Location: lib/kobject_uevent.c:277
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819d1d00-ffffffff819d1dbc: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0ade0)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a0ade0-ffffffff81a0ae9c: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a7a7c0)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a7a7c0-ffffffff81a7a87a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ab1b20)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ab1b20-ffffffff81ab1bda: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ec1b0)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
```
**Symbols:**

```
ffffffff815ec1b0-ffffffff815ec26a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81610990)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
```
**Symbols:**

```
ffffffff81610990-ffffffff81610a4a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815f4050)
Location: lib/kobject_uevent.c:279
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff815f4050-ffffffff815f410a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff816613c0)
Location: lib/kobject_uevent.c:279
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff816613c0-ffffffff8166147a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8177b160)
Location: lib/kobject_uevent.c:279
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff8177b160-ffffffff8177b228: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff82024360)
Location: lib/kobject_uevent.c:279
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff82024360-ffffffff82024428: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a4470)
Location: lib/kobject_uevent.c:279
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff820a4470-ffffffff820a4538: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217c540)
Location: lib/kobject_uevent.c:279
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff8217c540-ffffffff8217c608: alloc_uevent_skb (STB_LOCAL)
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
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffff800010d8be88)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010d8be88-ffff800010d8bf40: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c0e86240)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0e86240-c0e862ec: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c000000000ecd7b0)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000ecd7b0-c000000000ecd8bc: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffe0008b4e8c)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0008b4e8c-ffffffe0008b4f46: alloc_uevent_skb (STB_LOCAL)
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
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a50970)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a50970-ffffffff81a50a2a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0da70)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a0da70-ffffffff81a0db2a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81abcd60)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81abcd60-ffffffff81abce1a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *alloc_uevent_skb(struct kobj_uevent_env *env, const char *action_string, const char *devpath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ac91e0)
Location: lib/kobject_uevent.c:278
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ac91e0-ffffffff81ac929a: alloc_uevent_skb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
