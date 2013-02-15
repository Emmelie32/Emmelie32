Emmelie32
======04_Game
package
{
  import flash.display.Bitmap;
  import flash.display.BitmapData;
  import flash.display.MovieClip;
  import flash.display.Sprite;
  import flash.events.MouseEvent;
  

  
  public class Main extends Sprite
  {
  	private var _circle1: Circle1;
  	private var _circle2 : Circle2;
  	private var _circle3 : Circle3;
  	private var _circle4 : Circle4;
  	private var _circle5 : Circle5;
  	private var _circle6 : Circle6;
  	private var _circle7 : Circle7;
  	private var _circle8 : Circle8;
  	private var _bitmapData :BitmapData;
  	private var _bitmap :Bitmap;
  	private var _play_Btn : Play_Btn;

  	
    // private var __startMenu: StartMenu;
  
  	
  	public function Main():void
  	{
  		
  		//skapar bitmap på scenen
  		
  		_bitmapData = new BitmapData(680, 500, false, 0x000000);
  		_bitmap = new Bitmap(_bitmapData);
  		_bitmap.x = -90;
  		_bitmap.y = 0;
  		
  		addChild( _bitmap);
  		
  		_circle1= new Circle1();
  		_circle1.x = 250;
  		_circle1.y = 200;
  		addChild(_circle1);
  		
  		_circle2 = new Circle2();
  		_circle2.x = 250;
  		_circle2.y = 250;
  		addChild(_circle2);
  		
  		
  		_circle3 = new Circle3();
  		_circle3.x = 180;
  		_circle3.y = 250;
  		addChild(_circle3);
  		
  		_circle4= new Circle4();
  		_circle4.x = 300;
  		_circle4.y = 200;
  		addChild(_circle4);
  		
  		_circle5= new Circle5();
  		_circle5.x = 10;
  		_circle5.y = 50;
  		addChild(_circle5);
  		
  		
  		_circle6= new Circle6();
  		_circle6.x = 480;
  		_circle6.y = 50;
  		addChild(_circle6);
  		
  		_circle7= new Circle7();
  		_circle7.x = 490;
  		_circle7.y = 322;
  		addChild(_circle7);
  		
  		_circle8= new Circle8();
  		_circle8.x = 20;
  		_circle8.y = 320;
  		addChild(_circle8);
  		
  
  		
  	
  		
  		//buttonMode= true;
  		
  		_play_Btn= new Play_Btn();
  		_play_Btn.x = 210;
  		_play_Btn.y = 320;
  		addChild(_play_Btn);
