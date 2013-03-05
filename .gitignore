/*
 * Resume.java
 * ------------------------------------
 * Programmer:   Nathan Soucy
 * Contact Info: PO Box 286, Milford, NH 03055
 *               603-721-6632
 * ------------------------------------
 * This is a program that artfully prints out my resume to show you that I am a very competent programmer who 
 * knows how to code. I hope to obtain an awesome internship position where I can extend my programming skills greatly,
 * while learning new skills. I have all the skills, I just need the experience.
 */

import acm.program.*;
import acm.graphics.*;

public class Resume extends GraphicsProgram{
  
	public static final int APPLICATION_WIDTH = 750; //sets application width
	public static final int APPLICATION_HEIGHT = 900; //sets application height

	private static final int indent = 25; //How far to indent the first sentence
	private static final int headIndent = APPLICATION_WIDTH/3; //How far to indent the header
	private static final int start = 30; //The starting position of the text
	private static final int ln_sp = 15; //Add this per line (multiply by line number)
 
	public void run() {
		print_Personal_Information();
		print_Objective();
		print_Skills();
		print_ActAff();
		print_Awards();
		print_Education();

	}
	
	private void print_Personal_Information() {
		// Here is my personal information, as you can tell by the method name, I always try to use good, descriptive names for my methods
		GLabel name = new GLabel("Nathan Soucy", headIndent, start);
		name.setFont("Helvetica-Bold-35");
		GLabel address = new GLabel("PO Box 286, Milford, NH, 03055", headIndent, start+ln_sp);
		GLabel phone_number = new GLabel("603-721-6632", headIndent, start+ln_sp*2);
		GLabel email = new GLabel("Nathan.Soucy@iCloud.com", headIndent, start+ln_sp*3);
		 
		add(name);
		add(address);
		add(phone_number);
		add(email);
	}
	
	private void print_Objective() {
		//This would be my objective, so you know why I want this position. As you can see, I do have programming experience.
		GLabel objective = new GLabel("Objective", indent, start+ln_sp*6);
		objective.setFont("Helvetica-Bold-20");
		GLabel objective1 = new GLabel("To obtain an awesome internship where I can use all my existing skills in challenging tasks,", indent, start+ln_sp*7);
		GLabel objective2 = new GLabel("where I can learn so many new skills that I’ll need for my career,", indent, start+ln_sp*8);
		GLabel objective3 = new GLabel("and to be able to continue on my education path to be a software engineer.", indent, start+ln_sp*9);
		
		add(objective);
		add(objective1);
		add(objective2);
		add(objective3);
	}
	
	private void print_Skills() {
		// Here are the skills I have, for your viewing pleasure
		GLabel skills = new GLabel("Skills",indent,start+ln_sp*11);
		skills.setFont("Helvetica-Bold-20");
		
		GLabel computer_skills = new GLabel("Comuter Skills", indent+20, start+ln_sp*12);
		computer_skills.setFont("Helvetica-italic-15");
		
		// This would be my computer experience, I've taken them apart, worked with just about all software, programmed, et cetera.
		// If it's computer related, I know about it.  If there's a problem, I can fix it.
		GLabel comp_skill_1 = new GLabel("✦ Worked with computers for well over 10 years", indent, start+ln_sp*13);
		GLabel comp_skill_2 = new GLabel("✦ Used with Mac OS X, Windows, and Linux computers", indent, start+ln_sp*14);
		GLabel comp_skill_3 = new GLabel("✦ Demonstrable programming skills, including basic concepts such as decomposition and writing human readable code", indent, start+ln_sp*15);
		GLabel comp_skill_4 = new GLabel("✦ Demonstrable knowledge of Java", indent, start+ln_sp*16);
		GLabel comp_skill_5 = new GLabel("✦ Quickly learns most tasks needed when applicable", indent, start+ln_sp*17);
		
		GLabel eng_skills = new GLabel("Engineering Skills", indent+20, start+ln_sp*19);
		eng_skills.setFont("Helvetica-italic-15");
		
		// This is my software engineering experience. It's not much, but I know what I'm doing, and that's why I need an internship so I can gain much more experience. 
		GLabel eng_skill_1 = new GLabel("✦ Ability to think logically, and work through any problem", indent, start+ln_sp*20);
		GLabel eng_skill_2 = new GLabel("✦ Used Eclipse and Xcode IDE’s, with proficient experience in each", indent, start+ln_sp*21);
		GLabel eng_skill_3 = new GLabel("✦ Programmed this resume", indent, start+ln_sp*22);
		
		
		add(skills);
		add(computer_skills);
		add(comp_skill_1);
		add(comp_skill_2);
		add(comp_skill_3);
		add(comp_skill_4);
		add(comp_skill_5);
		
		add(eng_skills);
		add(eng_skill_1);
		add(eng_skill_2);
		add(eng_skill_3);
	}
	
	private void print_ActAff() {
		// Here are the programs I participated in where I learned everything I know about computer programming
		GLabel act_aff = new GLabel("Activities & Affiliations", indent, start+ln_sp*24);
		act_aff.setFont("Helvetica-Bold-20");
		
		// Stanford programming course I took on iTunes U
		GLabel act_aff1 = new GLabel("5/2012 - Current           Stanford Programing Methodologies course", indent, start+ln_sp*25);
		GLabel act_aff1_desc = new GLabel("✦ Learned the Java programming language, along with other general programming skills", indent, start+ln_sp*26);
		GLabel act_aff2_desc = new GLabel("✦ Successfully completed many Java projects", indent, start+ln_sp*27);
		
		// Accounting work, I'm also very good at accounting, so I'm prepared for any position to fulfill 
		GLabel act_aff2 = new GLabel("9/2009 - 6/2011           Accounting Classes", indent, start+ln_sp*29);
		GLabel act_aff3_desc = new GLabel("✦ Completed Accounting classes in high school and college", indent, start+ln_sp*30);
		GLabel act_aff4_desc = new GLabel("✦ Prepared financial worksheets and organized expense reports in a mock accounting settin", indent, start+ln_sp*31);
		
		add(act_aff);
		add(act_aff1);
		add(act_aff1_desc);
		add(act_aff2_desc);
		add(act_aff2);
		add(act_aff3_desc);
		add(act_aff4_desc); 
	}
	
	private void print_Awards() {
		// These are the awards I've received for my excellent work (Well, I only have 1 now, but I'll have more eventually!)
		GLabel awd_hon = new GLabel("Awards & Honors", indent, start+ln_sp*33);
		awd_hon.setFont("Helvetica-Bold-20");
		
		GLabel award1 = new GLabel("6/2010         Marketing Most Improved Milford High School", indent, start+ln_sp*34);
		GLabel award_desc = new GLabel("Obtained the Marketing Most Improved Award for Marketing II", indent, start+ln_sp*35);
		
		add(awd_hon);
		add(award1);
		add(award_desc);
	}
	
	private void print_Education() {
		// Now, here's my education experience. This is also where all my experience comes from.
		GLabel edu = new GLabel("Education",indent,start+ln_sp*37);
		edu.setFont("Helvetica-Bold-20");
		
		//This would be my high school, I did very well in some classes I enjoyed very much, where the teacher made the class enjoyable, but in other classes I quickly got bored and didn't do so well.
		//However, I am very interested in programming, so I would do very well in it, I just need more hands on experience.
		GLabel school1 = new GLabel("9/2006 - 6/2010          Milford High School          Milford, NH", indent, start+ln_sp*38);
		//I'm still going to this school, but I've put it on hold due to financial reasons, I'd love to be able to go back, though, so this internship is extremely important to me.
		GLabel school2 = new GLabel("9/2010 - 6/2012          Berkeley College              Woodland Park, NJ", indent, start+ln_sp*39);
		//This is where I learned my programming skills, I wont get any degree, but I did get lots of skills!
		GLabel school3 = new GLabel("5/2012 - Current           Stanford (iTunes U)          Online", indent, start+ln_sp*40);
		
		add(edu);
		add(school1);
		add(school2);
		add(school3);
	
	}
}

