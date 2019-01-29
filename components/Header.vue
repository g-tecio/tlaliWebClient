 <template>
 <div>
     <script src="https://unpkg.com/vue"></script>
     <script src="https://unpkg.com/vue-resize-text"></script>
     <br>
     <br>
 <p id="txti" style="align:center">Tlali</p>

    <div  class="imagenes" >
      <a href="https://www.facebook.com/DgoNoticias/" title="Facebook"><img  src="@/assets/fb.png" class="imgfb"></a>
      <a href="https://twitter.com/DgoNoticias/" title="Twitter"><img src="@/assets/twi.png" class="imgtwi"></a>
      <a href="https://feedly.com/i/subscription/feed/https://dgonoticias.ghost.io/rss/" title="Feedly"><img src="@/assets/fed.png" class="imgfed"></a>
    </div>
      <hr id="hr1">
      <br>
      <br>
</div>
</template>

  <style scoped>
  
#hr1 {
  height: 10px;
  margin-left: 450px;
  background-color:red;
  border: none;
  /* height: 10px; */
  width: 60%;
  
}
#txti{
font-family: 'Lucida Sans';
color: midnightblue;
  margin-left: 450px;
  
 padding: 0 15px; 
/* margin: 50px; */
font-size: 27px;
align-content: center;
font-weight: bold;
}

.imagenes{
  margin-left: 1220px;
  display: flex;
}

.imgfb{
  width: 20;
  height: 30px;
}
.imgfb:hover{
  background-color: burlywood;
}

.imgtwi{
  width: 20;
  height: 30px; 
  margin-left: 10px;
}
.imgfed{
  width: 20;
  height: 30px; 
  margin-left: 10px;
}

</style>