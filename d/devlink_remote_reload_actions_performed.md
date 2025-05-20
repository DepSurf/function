# Function: <code>devlink_remote_reload_actions_performed</code>

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
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a67180)
Location: net/core/devlink.c:3164
Inline: False
```
**Symbols:**

```
ffffffff81a67180-ffffffff81a671b4: devlink_remote_reload_actions_performed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a370)
Location: net/core/devlink.c:3367
Inline: False
```
**Symbols:**

```
ffffffff81a4a370-ffffffff81a4a3a4: devlink_remote_reload_actions_performed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b023d0)
Location: net/core/devlink.c:3932
Inline: False
```
**Symbols:**

```
ffffffff81b023d0-ffffffff81b02404: devlink_remote_reload_actions_performed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85e40)
Location: net/core/devlink.c:4447
Inline: False
```
**Symbols:**

```
ffffffff81c85e40-ffffffff81c85e8f: devlink_remote_reload_actions_performed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e40160)
Location: net/core/devlink.c:4713
Inline: False
```
**Symbols:**

```
ffffffff81e40160-ffffffff81e401af: devlink_remote_reload_actions_performed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82044530)
Location: net/devlink/dev.c:284
Inline: False
```
**Symbols:**

```
ffffffff82044530-ffffffff8204457f: devlink_remote_reload_actions_performed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_remote_reload_actions_performed(struct devlink *devlink, enum devlink_reload_limit limit, u32 actions_performed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82103430)
Location: net/devlink/dev.c:363
Inline: False
```
**Symbols:**

```
ffffffff82103430-ffffffff8210347f: devlink_remote_reload_actions_performed (STB_GLOBAL)
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
