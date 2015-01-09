package controllers;

import play.*;
import play.mvc.*;

import views.html.*;

import static scala.collection.JavaConversions.asScalaBuffer;
public class Application extends Controller {

    public static Result index() {
    	int level = 1;
    	java.util.List<String> list = java.util.Arrays.asList("me", "and you", "for me", "etc");
        return ok(index.render("It works!", level, asScalaBuffer(list)));
    }
}
