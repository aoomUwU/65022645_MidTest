import org.junit.Test;
import org.junit.Before;
import static org.junit.Assert.*;

public class testCoreFunction {
	public QuizOneJunit obj;
	
	@Before
	public void init() {
		obj = new QuizOneJunit();
	}
	@Test
	public void wordTC1() {
		assertEquals(2, obj.countLetterA("cAca"));
	}
	@Test
	public void wordTC2() {
		assertEquals(0, obj.countLetterA("c"));
	}
	@Test
	public void wordTC3() {
		assertEquals(0, obj.countLetterA(""));
	}
	
	@Test
	public void letterTC1() {
		assertEquals(false, obj.checkTwoLetter("a"));
	}
	@Test
	public void letterTC2() {
		assertEquals(true, obj.checkTwoLetter("ab"));
	}
	@Test
	public void letterTC3() {
		assertEquals(true, obj.checkTwoLetter("abab"));
	}
}
