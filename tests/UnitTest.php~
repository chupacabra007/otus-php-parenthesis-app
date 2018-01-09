<?php

use Phalcon\Di;
use PHPUnit\Framework\TestCase as TestCase;
use chupacabra007\parenthesis\Checker;


class UnitTest extends TestCase
{
    
    public function testBalanced()
    {
        $this->assertTrue(
            Checker::check('()')
        );       
    }
    
    public function testNotBalanced()
    {
        $this->assertFalse(
            Checker::check('(()')
        );       
    }
}