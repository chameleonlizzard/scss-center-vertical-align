<h1>SCSS Center Vertical Align Mixin</h1>

<h2>How to use</h2>

<p>Add to the container:</p>

<p>First at the mixin to the scss page</p>
<code>
@import "_mixin.valign.scss";
</code>

<p>Add the following code to your container where the content has to be vertical centered:</p>
<p>
<code>
.container {
    @include valign-container($width: value, $min-height: value);
}
</code>
</p>

<p>Add the following code to your content inside the container who has to be vertical centered:</p>

<code>
.content {
    @include valign-content();
}
</code>