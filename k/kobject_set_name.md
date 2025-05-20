# Function: <code>kobject_set_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ebe30)
Location: lib/kobject.c:300
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff813ebe30-ffffffff813ebe95: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff814321d0)
Location: lib/kobject.c:300
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff814321d0-ffffffff81432235: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e440)
Location: lib/kobject.c:300
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff8144e440-ffffffff8144e4a5: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee6e0)
Location: lib/kobject.c:300
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff818ee6e0-ffffffff818ee745: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819749a0)
Location: lib/kobject.c:300
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff819749a0-ffffffff81974a05: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0fa0)
Location: lib/kobject.c:316
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff819d0fa0-ffffffff819d1005: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a500)
Location: lib/kobject.c:316
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a0a500-ffffffff81a0a565: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79e60)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a79e60-ffffffff81a79ec5: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab11c0)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81ab11c0-ffffffff81ab1225: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eb700)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
**Symbols:**

```
ffffffff815eb700-ffffffff815eb765: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81610020)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
**Symbols:**

```
ffffffff81610020-ffffffff81610085: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f3760)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff815f3760-ffffffff815f37c5: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81660930)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff81660930-ffffffff81660995: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8177a460)
Location: lib/kobject.c:292
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - lib/kobject.c:kset_create_and_add
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff8177a460-ffffffff8177a4df: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82023580)
Location: lib/kobject.c:300
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff82023580-ffffffff820235ff: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a35f0)
Location: lib/kobject.c:301
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff820a35f0-ffffffff820a366f: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b670)
Location: lib/kobject.c:308
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff8217b670-ffffffff8217b6ef: kobject_set_name (STB_GLOBAL)
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
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b590)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffff800010d8b590-ffff800010d8b608: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e8588c)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - sound/core/init.c:snd_card_new
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
c0e8588c-c0e858e8: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecc8f0)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
c000000000ecc8f0-c000000000ecc934: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b45fc)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffe0008b45fc-ffffffe0008b462a: kobject_set_name (STB_GLOBAL)
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
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a50010)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a50010-ffffffff81a50075: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0d110)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81a0d110-ffffffff81a0d175: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abc400)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81abc400-ffffffff81abc465: kobject_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kobject_set_name(struct kobject *kobj, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8880)
Location: lib/kobject.c:324
Inline: False
Direct callers:
  - fs/char_dev.c:__register_chrdev
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - lib/kobject.c:kset_create_and_add
```
**Symbols:**

```
ffffffff81ac8880-ffffffff81ac88e5: kobject_set_name (STB_GLOBAL)
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
