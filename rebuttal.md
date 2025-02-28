## Anonymous repository for paper submission: ICLR 2025, paper ID 1844

# Rebuttal--Supplementary Visual Results

## Pixel-level Control & Visual Comparisons

We show our camera control results with ground truth preview here, which demonstrates our pixel-level control capabilities.

We also list the results of the comparing methods for the qualitative comparison. We can observe that our control precision is significantly higher than that of comparative methods.

<table>
  <tr>
    <th width=25% style="text-align:center">Input & GT Preview</th>
    <th width=25% style="text-align:center">CameraCtrl</th>
    <th width=25% style="text-align:center">MotionCtrl</th>
    <th width=25% style="text-align:center">Ours</th>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/004-3.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/006-2.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/007-3.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/011-0.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241001223430.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241002000913.gif"></td>
  </tr>
</table>


## Combinations of multiple camera movements

The following samples contain combinations of multiple camera movements.

<table>
  <tr>
    <th width=20% style="text-align:center">Camera Mode</th>
    <th width=20% style="text-align:center">Input & GT Preview</th>
    <th width=20% style="text-align:center">CameraCtrl</th>
    <th width=20% style="text-align:center">MotionCtrl</th>
    <th width=20% style="text-align:center">Ours</th>
  </tr>
  <tr>
    <th width=20% style="text-align:center">move left + pan right + move up + tilt down</th>
    <td colspan="4" ><img src="assets/pixel/20241002002519.gif"></td>
  </tr>
  <tr>
    <th width=20% style="text-align:center">move left + pan right</th>
    <td colspan="4" ><img src="assets/pixel/20240906132533.gif"></td>
  </tr>
  <tr>
    <th width=20% style="text-align:center">rotate + move up + tilt down</th>
    <td colspan="4" ><img src="assets/pixel/20241120012823.gif"></td>
  </tr>
  <tr>
    <th width=20% style="text-align:center">rotate + zoom in</th>
    <td colspan="4" ><img src="assets/pixel/20241120011336.gif"></td>
  </tr>
  <tr>
    <th width=20% style="text-align:center">rotate + pan right</th>
    <td colspan="4" ><img src="assets/pixel/20241120015213.gif"></td>
  </tr>
</table>


## Multiple dynamic objects

The following samples contain multiple dynamic objects, where our method can still achieve precise control and natural dynamics.


<table>
  <tr>
    <th width=25% style="text-align:center">Input & GT Preview</th>
    <th width=25% style="text-align:center">CameraCtrl</th>
    <th width=25% style="text-align:center">MotionCtrl</th>
    <th width=25% style="text-align:center">Ours</th>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241120024444.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241120030823.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241120034631.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241120041540.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/20241121033649.gif"></td>
  </tr>
</table>


## Multiple motion strength

We show the results under different motion strength. It is evident that as the motion strength increases, the amplitude of the motions enlarged and shows a direct positive correlation with the set values of motion strength.


<table>
  <tr>
    <th width=25% style="text-align:center">Input & GT Preview</th>
    <th width=25% style="text-align:center">MS=0</th>
    <th width=25% style="text-align:center">MS=200</th>
    <th width=25% style="text-align:center">MS=600</th>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_0.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_1.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_2.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_3.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_4.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_5.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_6.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_7.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="assets/pixel/range_8.gif"></td>
  </tr>
</table>



## Experiment on another base model

We present some preliminary results on another base model. Although we are not yet able to present very detailed experimental results (due to limited time), the current results should be sufficient to demonstrate the applicability of our method to any base model.


<table>
  <tr>
    <th width=25% style="text-align:center">Pan</th>
    <th width=25% style="text-align:center">Zoom</th>
    <th width=25% style="text-align:center">Tilt</th>
    <th width=25% style="text-align:center">Rotate</th>
  </tr>
  <tr>
    <td colspan="1" ><img src="assets/pixel/seaweed_pan.gif"></td>
    <td colspan="1" ><img src="assets/pixel/seaweed_zoom.gif"></td>
    <td colspan="1" ><img src="assets/pixel/seaweed_tilt.gif"></td>
    <td colspan="1" ><img src="assets/pixel/seaweed_rotate.gif"></td>
  </tr>
  <tr>
    <td colspan="1" ><img src="assets/pixel/seaweed_pan2.gif"></td>
    <td colspan="1" ><img src="assets/pixel/seaweed_zoom2.gif"></td>
    <td colspan="1" ><img src="assets/pixel/seaweed_tilt2.gif"></td>
    <td colspan="1" ><img src="assets/pixel/seaweed_rotate2.gif"></td>
  </tr>
</table>


## Visualization of dynamic mask

Some representative examples are illustrated below. Our method successfully classifies subjects exhibiting substantial motion into dynamic segments with a high degree of accuracy.

<table>
  <tr>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+26357585.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+45636767.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+101776714.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+106529640.gif"></td>
  </tr>
  <tr>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+193535445.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+141908344.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+185810975.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+195560416.gif"></td>
  </tr>
</table>

As suggested by the reviewer, we specifically selected some examples featuring lake/sea/water, which are showcased below:

<table>
  <tr>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+37280830.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+40120911.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+40736998.gif"></td>
    <td colspan="1" ><img src="assets/motion_mask/123RF+packed_2+m0_000000+110499692.gif"></td>
  </tr>
</table>

