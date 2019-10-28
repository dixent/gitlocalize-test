<table class="noborder">
<tr>
    <td colspan="2"><h5 id="fill">Template: Fill</h5></td>
</tr>
<tr>
    <td width="65%">The <strong>fill</strong> template fills the screen with the first child element in the layer. Any other children in this layer aren't shown.

    The fill template works well for backgrounds, including images and videos.
   <code class="nopad"><pre>&lt;amp-story-grid-layer template="fill">
  &lt;amp-img src="dog.png"
      width="720" height="1280"
      layout="responsive">
  &lt;/amp-img>
&lt;/amp-story-grid-layer></pre></code>
    </td>
    <td>
    {{ image('/static/img/docs/tutorials/amp_story/layer-fill.png', 216, 341) }}
    </td>
</tr>
</table>
